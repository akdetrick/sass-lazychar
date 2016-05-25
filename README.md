sass-lazychar
=============

### Use HTML entity and emoji names in your Sass!

#### ⚠️ work in progress ⚠️

```scss
.wat:before {
	content: emoji("LOVE HOTEL");
}

.text--middotLeft:before {
	content: entity("middot");
	margin: auto 0.5em;
}

.breadcrumb:after {
	content: entity("gt");
	margin: auto 0.5em;

	&:last-child {
		display: none;
	}
}
```

