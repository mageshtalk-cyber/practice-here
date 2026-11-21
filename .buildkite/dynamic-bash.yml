#!/bin/bash
set -euo pipefail

echo "steps:"
for target in dev staging prod; do
  cat <<EOF
  - label: "deploy to ${target}"
    command: echo "deploying to ${target}"
  EOF
  done
