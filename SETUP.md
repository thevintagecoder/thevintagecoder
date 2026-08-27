# Fix applied

This version removes blank lines from inside multi-line HTML tags and keeps image tags compact.
GitHub's Markdown renderer was treating the split `<img ... />` block as literal text.

After replacing the files:
1. Commit and push.
2. Refresh the profile.
3. Run all three Actions once:
   - Latest Medium Articles
   - Generate Westeros War Map
   - GitHub-Profile-3D-Contrib
