Notes of PHYS 201A

To enable git commit hook:
```
touch .git/hooks/post-commit
echo 'echo "Start to build and deploy ..."\nnpm run build && npm run deploy' > .git/hooks/post-commit
chmod +x .git/hooks/post-commit
```
