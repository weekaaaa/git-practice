git add README.md
git commit -m "仕様を README に書く"
gh repo create git-practice --public --source=. --push
gh repo view --web