# DevKit CLI

A pocket CLI for everyday developer chores

## Overview
DevKit CLI is a small command-line tool for common developer tasks, packaged as a single downloadable bundle for Node 18+. It combines six practical utilities—such as JSON formatting, Base64 encoding and decoding, UUID generation, hashing, timestamp conversion, and .env validation—without requiring additional npm packages. It is intended for developers who want quick local helpers without adding dependencies to a project.

## Use cases
- You need to pretty-print and validate a JSON payload copied from an API response before saving it as a test fixture.
- You are debugging a webhook and need to decode a Base64 token or generate a UUID for a temporary test record.
- You want to calculate a file hash or convert a Unix timestamp while inspecting logs on a machine where installing extra CLI tools is inconvenient.

## How to use
1. Download the appbundle and extract it to a convenient folder.
2. Confirm Node 18 or newer is installed, then run the included entry point with Node.
3. Run the help command to see the six utilities and their flags, then invoke the one you need with your input.

## What is included
- Six real utilities in one binary
- Zero dependencies
- Works with Node 18+

## License
Personal use. Redistribution not permitted.
