
rm -rf ~/.claude/commands
mkdir ~/.claude/commands
rsync -av --delete /workspace/claude-code-commands/commands/ ~/.claude/commands/

ln -s /workspace/claude-code-commands/commands ~/.claude