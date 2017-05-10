demonstration of issue at https://github.com/facebook/jest/issues/971

- run `yarn fail` to run a test that SHOULD pass, but crashes
- run `yarn pass` to run a test that passes due to a different order of `import` statements, which shouldn't matter

