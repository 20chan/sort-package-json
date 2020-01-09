# Snapshot report for `tests/eslint.js`

The actual snapshot is saved in `eslint.js.snap`.

Generated by [AVA](https://ava.li).

## eslintConfig

> Should sort `eslintConfig` as object.

    `{␊
      "eslintConfig": {␊
        "env": "env",␊
        "parser": "parser",␊
        "parserOptions": "parserOptions",␊
        "settings": "settings",␊
        "plugins": "plugins",␊
        "extends": "extends",␊
        "rules": "rules",␊
        "overrides": "overrides",␊
        "globals": "globals",␊
        "processor": "processor",␊
        "noInlineConfig": "noInlineConfig",␊
        "reportUnusedDisableDirectives": "reportUnusedDisableDirectives",␊
        "a": "a",␊
        "z": "z"␊
      }␊
    }`

## eslintConfig.override[]

> Should sort `eslintConfig.override[]` same as `eslintConfig`

    `{␊
      "eslintConfig": {␊
        "overrides": [␊
          {␊
            "files": "*.js",␊
            "excludedFiles": "*.exclude.js",␊
            "env": "env",␊
            "parser": "parser",␊
            "parserOptions": "parserOptions",␊
            "settings": "settings",␊
            "plugins": "plugins",␊
            "extends": "extends",␊
            "rules": "rules",␊
            "overrides": "overrides",␊
            "globals": "globals",␊
            "processor": "processor",␊
            "noInlineConfig": "noInlineConfig",␊
            "reportUnusedDisableDirectives": "reportUnusedDisableDirectives",␊
            "_": "this should still be the first element"␊
          },␊
          {␊
            "files": "*.js",␊
            "excludedFiles": "*.exclude.js",␊
            "env": "env",␊
            "parser": "parser",␊
            "parserOptions": "parserOptions",␊
            "settings": "settings",␊
            "plugins": "plugins",␊
            "extends": "extends",␊
            "rules": "rules",␊
            "overrides": "overrides",␊
            "globals": "globals",␊
            "processor": "processor",␊
            "noInlineConfig": "noInlineConfig",␊
            "reportUnusedDisableDirectives": "reportUnusedDisableDirectives",␊
            "_": "this should still be the second element"␊
          }␊
        ]␊
      }␊
    }`