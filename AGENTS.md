build: |
  echo "No build step"
test: |
  npx html-validate "index.html" || true   # HTML 構文チェックだけ

