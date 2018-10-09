# A collection of customizable Nova Fields

## WIP

We are working on a rewrite of every "native" field that comes with Nova.

The idea is make them more configurable and reusable in package development. If you like the idea you can collaborate with us with your awesome PRs!

Available fields:

- ID
- Text
- Number
- Textarea
- Select
- Password
- Boolean
- Trix
- File
- Image
- BelongsTo

- Row
- JSON

Some examples:

```php
Boolean::make('Activo', 'active')
                ->yesLabel('Yeah')
                ->noLabel('Nope')
                ->hideLabelInDetail()
                ->dotClasses('some classes')
                ->successClass('bg-warning')
```

We are also adding events in vue components that propagates up to the chain so the parent notices when something has happened

Looking forward to see your feedback.

### Install

Run this command in your nova project:
`composer require 64robots/nova-fields`
