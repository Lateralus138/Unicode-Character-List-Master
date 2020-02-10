# Unicode Hexadecimal Codes

This is a list of [Unicode](https://duckduckgo.com/?q=unicode&ia=web)<sup>[1](#note1)</sup> hexadecimal codes that are representitive of all the characters &amp; emojis in most of the various languages of the world.

This list was generated using the scripting language [AutoHotkey](https://www.autohotkey.com/)<sup>[2](#note2)</sup>. I will be generating more lists and eventually combining them into a list with no blanks and a master list.

## Disclaimer

This is a temporary project site &amp; it will eventually be on a website or blog.

## How to read &amp; use this list

Each set is listed from; for example:

- 0x0000-0x1FFF (0x000-0xFFF or 0-8192)

- 0x1F000-0x1FFFF (0x000-0xFFF or 0-4096)

### Examples

- 0x1F000 = 0x0 = 🀀
- 0x1F0FF = 0xFF = 🃿
- 0x1F100 = 0x0 = 🄀
- 0x1F1FF = 0xFF = 🇿
- 0x1F4FA = 0xFA = 📺
- 0x1F451 = 0x51 = 👑
- 0x1F31F = 0x1F = 🌟
- 0x00C6 = 0xC6 = Æ

### AutoHotkey Usage<sup>[3](#note3)</sup>

- Chr() or Send[Input|Raw] or MsgBox
  - Chr(0x1F000) ; 🀀
  - SendInput,{U+0x1F000} ; 🀀
  - MsgBox,64,Unicode Emoji,% Chr(0x1F451) ; 👑

### Linux Usage

- \<Shift\>+\<Control\>+u+\<hex\>
  - \<Shift\>+\<Control\>+u+\<0x1F000\> # 🀀
  - \<Shift\>+\<Control\>+u+\<0x1F451\> # 👑

<a name="list"></a>

## List

### Index

- [0x0000-0x1FFF](https://github.com/Lateralus138/Unicode-Char-List-0x0000-0x1FFF)
  - [0x0000-0x0FFF](https://github.com/Lateralus138/Unicode-Char-List-0x0000-0x1FFF#0x0000)
  - [0x1000-0x1FFF](https://github.com/Lateralus138/Unicode-Char-List-0x0000-0x1FFF#0x1000)
- [0x2000-0x3FFF](https://github.com/Lateralus138/Unicode-Char-List-0x2000-0x3FFF)
  - [0x2000-0x2FFF](https://github.com/Lateralus138/Unicode-Char-List-0x2000-0x3FFF#0x2000)
  - [0x3000-0x3FFF](https://github.com/Lateralus138/Unicode-Char-List-0x2000-0x3FFF#0x3000)

- [0x4000-0x5FFF](https://github.com/Lateralus138/Unicode-Char-List-0x4000-0x5FFF)
  - [0x4000-0x4FFF](https://github.com/Lateralus138/Unicode-Char-List-0x4000-0x5FFF#0x4000)
  - [0x5000-0x5FFF](https://github.com/Lateralus138/Unicode-Char-List-0x4000-0x5FFF#0x5000)
- [0x6000-0x7FFF](https://github.com/Lateralus138/Unicode-Char-List-0x6000-0x7FFF)
  - [0x6000-0x6FFF](https://github.com/Lateralus138/Unicode-Char-List-0x6000-0x7FFF#0x6000)
  - [0x7000-0x7FFF](https://github.com/Lateralus138/Unicode-Char-List-0x6000-0x7FFF#0x7000)

- [0x8000-0x9FFF](https://github.com/Lateralus138/Unicode-Char-List-0x8000-0x9FFF)
  - [0x8000-0x8FFF](https://github.com/Lateralus138/Unicode-Char-List-0x8000-0x9FFF#0x8000)
  - [0x9000-0x9FFF](https://github.com/Lateralus138/Unicode-Char-List-0x8000-0x9FFF#0x9000)
- [0xA000-0xBFFF](https://github.com/Lateralus138/Unicode-Char-List-0xA000-0xBFFF)
  - [0xA000-0xAFFF](https://github.com/Lateralus138/Unicode-Char-List-0xA000-0xBFFF#0xA000)
  - [0xB000-0xBFFF](https://github.com/Lateralus138/Unicode-Char-List-0xA000-0xBFFF#0xB000)

- [0xC000-0xDFFF](https://github.com/Lateralus138/Unicode-Char-List-0xC000-0xDFFF)
  - [0xC000-0xCFFF](https://github.com/Lateralus138/Unicode-Char-List-0xC000-0xDFFF#0xC000)
  - [0xD000-0xDFFF](https://github.com/Lateralus138/Unicode-Char-List-0xC000-0xDFFF#0xD000)
- [0xE000-0xFFFF](https://github.com/Lateralus138/Unicode-Char-List-0xE000-0xFFFF)
  - [0xE000-0xEFFF](https://github.com/Lateralus138/Unicode-Char-List-0xE000-0xFFFF#0xE000)
  - [0xF000-0xFFFF](https://github.com/Lateralus138/Unicode-Char-List-0xE000-0xFFFF#0xF000)

- [0x1F000-0x1FFFF](https://github.com/Lateralus138/Unicode-Char-List-0x1F000-0x1FFFF)
  - [0x1F000-0x1FFFF](https://github.com/Lateralus138/Unicode-Char-List-0x1F000-0x1FFFF#0x1F000)

### Footnotes

<a name="note1">[1]</a>: Unicode is the computer standard of universal character &amp; emoji sets of all languages around the world. 

<a name="note2">[2]</a>: Both the characters &amp; HTML tables were generated with AHK.

<a name="note3">[3]</a>: I'm currently working on a program to help send these characters in Windows.
