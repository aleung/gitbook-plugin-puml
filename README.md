# PlantUML in GitBook

> **Note**:
>
> This is a fork of the [gitbook-plugin-puml](https://www.npmjs.com/package/gitbook-plugin-puml) to fix issues.
> The original project was out of maintenance.

UML Diagrams rendering using PlantUML.

[![NPM version](https://badge.fury.io/js/gitbook-plugin-puml-aleung.svg)](http://badge.fury.io/js/gitbook-plugin-puml-aleung)


Configure the plugin in your `book.json`:

```js
{
    "plugins": ["puml-aleung"]
}
```

Then in your content:

```md
This is a diagram:

{% plantuml %}
Bob->Alice : hello
{% endplantuml %}
```

The plugin will replace the `{% plantuml %}` by SVG images (and PNG images for ebook output).
