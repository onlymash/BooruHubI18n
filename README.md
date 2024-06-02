# BooruHub internationalization and localization

## Translation Guide

1. Copy `res/values/strings.xml` to `res/values-[language code]-r[country code]/strings.xml` and begin your translation.

2. Once you have completed the translation, update `res/values/arrays_i18n.xml` with your translation details, including the language name and the translator's name. If there are multiple translators, separate their names with commas: `, `. Ensure that the order of the two arrays matches exactly; do not mix up the sequence.

Example:
```
    <!-- Language name array -->
	<string-array name="i18n_lang">
		<item name="zh_cn">🇨🇳 简体中文</item>
	</string-array>
	<!-- Translator name array -->
	<string-array name="i18n_translator">
		<item name="zh_cn">onlymash</item>
	</string-array>
```
