git clone https://github.com/ggobbler/EBP-Figma-Design-System-Sync.git
cd EBP-Figma-Design-System-Sync
mkdir design-tokens
touch design-tokens/.gitkeep
echo "# Design Tokens" > README.md
git add .
git commit -m "Initial commit with design-tokens directory"
git push origin main
