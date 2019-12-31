# VaulVulp's dotfiles

## [YAPF](https://github.com/google/yapf)

Config file may be stored at the home directory: `~/.config/yapf/style` 

```ini
[style]
BASED_ON_STYLE = chromium
INDENT_WIDTH = 4
ALIGN_CLOSING_BRACKET_WITH_VISUAL_INDENT = True
BLANK_LINE_BEFORE_NESTED_CLASS_OR_DEF = True
COALESCE_BRACKETS = True
COLUMN_LIMIT = 120
DEDENT_CLOSING_BRACKETS = True
EACH_DICT_ENTRY_ON_SEPARATE_LINE = True
INDENT_DICTIONARY_VALUE = True
SPACES_AROUND_POWER_OPERATOR= True
SPLIT_ARGUMENTS_WHEN_COMMA_TERMINATED = True
SPLIT_BEFORE_DICT_SET_GENERATOR = True
SPLIT_BEFORE_EXPRESSION_AFTER_OPENING_PAREN = True
SPLIT_BEFORE_FIRST_ARGUMENT = True
ALLOW_SPLIT_BEFORE_DICT_VALUE = False
```

## [isort](https://github.com/timothycrosley/isort)

Config file may be stored at the home directory: `~/.isort.cfg`

```ini
[settings]
line_length=120
multi_line_output=3
include_trailing_comma=1
```