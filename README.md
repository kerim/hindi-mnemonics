# Hindi Vocabulary Mnemonics Skill

A Claude skill for generating unforgettable Hindi vocabulary mnemonics using sound matching and vivid imagery.

## What This Skill Does

This skill helps you create memorable mnemonics for Hindi vocabulary words by:

- **Sound matching**: Finding English words/phrases that match the Hindi pronunciation
- **Direct imagery**: Using words that directly relate to the target meaning
- **Idiomatic phrases**: Leveraging common expressions that convey the meaning as a whole
- **Unforgettable scenarios**: Creating funny, shocking, or absurd imagery that sticks in your memory

## Installation

### For Claude Code

1. Clone or download this repository
2. Copy the `skill/` folder to your Claude Code skills directory:
   ```bash
   cp -r skill ~/.claude/skills/mnemonics
   ```
3. Restart Claude Code to load the skill

### Alternative: Direct Download

1. Download just the `skill/` folder from this repository
2. Rename it to `mnemonics` and place it at `~/.claude/skills/mnemonics/`
3. Restart Claude Code

## Usage

Simply ask Claude to create mnemonics for Hindi words:

```
Create mnemonics for स्वादिष्ट
```

You'll get 5 different mnemonic options, each with:
- The Hindi word and meaning
- A mnemonic phrase with sound-matched words
- Sound mapping showing how it matches
- A vivid, memorable image description

## Examples

### Direct Imagery

**Word**: सूरज (sūraj)
**Meaning**: sun

**Mnemonic**: SOARING RAYS
**Sound mapping**: SŌR(-ing) RAYS → सूरज
**Image**: Rays of sunlight soaring upward from the horizon at dawn

### Idiomatic Phrases

**Word**: आवाज़ (āvāz)
**Meaning**: voice, sound

**Mnemonic**: AS I VUZ saying
**Sound mapping**: AZ I VUZ → आवाज़ (with "I was" pronounced with slight lisp/German accent)
**Image**: Someone repeatedly saying "as I was saying" to regain attention - their voice trying to be heard

**Word**: अंतिम (antim)
**Meaning**: final, last

**Mnemonic**: for the UMpTEENth time!
**Sound mapping**: UM-TEEN(th) → अंतिम
**Image**: Someone exasperatedly saying "for the umpteenth time!" - implying this is the final warning

## Core Principles

1. **Flexible sound matching**: First syllable should match closely, but idiomatic phrases can have slightly off first syllables if they have excellent second syllable matches
2. **Direct imagery**: Words should inherently evoke the meaning, not require forcing connections
3. **Unforgettable**: Mnemonics must be funny, shocking, absurd, or surprising - boring mnemonics don't work!
4. **Complete coverage**: Aim to capture all syllables when possible

## What Makes a Good Mnemonic

✅ **GOOD**:
- Words directly relate to the meaning
- Funny, shocking, or absurd imagery
- Idiomatic phrases that naturally convey the meaning
- Makes you think "That's ridiculous... but I'll never forget it!"

❌ **BAD**:
- Round-about connections where meaning is added as scenery
- Boring, forgettable imagery
- Generic phrases without emotion
- Sound matches that force unrelated meanings

## Contributing

Found a great mnemonic? Have suggestions for improvement? Please open an issue or pull request!

## License

MIT License - feel free to use, modify, and share!

## Author

Created for learning Hindi vocabulary with Claude AI.
