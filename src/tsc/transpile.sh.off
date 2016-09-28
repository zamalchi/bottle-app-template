#!/bin/bash

parent_path=$( cd "$(dirname "${BASH_SOURCE}")" ; pwd -P )

ts_file="./main.ts"
js_file="../../static/js/main.js"

cd $parent_path

tsc --watch --outFile ${js_file} ${ts_file}
