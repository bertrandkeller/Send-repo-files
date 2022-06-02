curl \
  -X PUT \
  -H "Accept: application/vnd.github.v3+json" \
  https://api.github.com/repos/bertrandkeller/quickaudit/readme.md \
  -d '{"message":"message","content":"content"}'

  0bfd573acd335330dd9f1b66f5bcf4ecfe927399
@