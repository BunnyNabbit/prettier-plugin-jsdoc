# prettier-plugin-drone-jsdoc

This is a fork of the [prettier-plugin-jsdoc](https://github.com/hosseinmd/prettier-plugin-jsdoc) Prettier plug-in. It removes the leading whitespace on multi-line block comments.

```js
// prettier-plugin-jsdoc

/**
 * Creates a new drone instance.
 *
 * @param {Ego} ego - The drone's appearance.
 */

// prettier-plugin-drone-jsdoc

/**Creates a new drone instance.
 *
 * @param {Ego} ego - The drone's appearance.
 */

// Single-line comments are unæffected.

/** Starts the stopwatch. */
```

## Why?

This is just how comments conform to the Drone style guide. I have JSDoc comments automatically folded on my editor. Being able to see the first line is helpful.
