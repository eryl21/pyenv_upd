#!/usr/bin/env bash
set -e
[ -n "$PYENV_DEBUG" ] && set -x

program="${0##*/}"

export PYENV_ROOT="/home/ecua/.pyenv"
exec "/home/ecua/.pyenv/libexec/pyenv" exec "$program" "$@"
