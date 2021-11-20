# Switch component

## Semantic HTML

As a building block, you will use the `input type="checkbox"` since its similarity with the switch behavior, also meet the progressive enhancement goal, ensuring that for older browsers like Internet Explorer 11 the fallback is a functional element.

## Accessibility concerns

To achieve the accessibility goal, our switch needs to meet three requirements:

### Focus and outline visibility

When users navigate using the keyboard with `TAB`, the switch component must present the default outline effect applied by default for browsers.

### Keyboard navigation and interaction

In addition to the keyboard navigation using `TAB`, users must be able to interact with the switch using the `space` key.

### Screen readers

The switch must work as well for screen readers, and using the above semantic HTML structure you don't need to include aria attributes.

The expected narration audio for the switch is:
`[unchecked,Feature,checkbox]`
