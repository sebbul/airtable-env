# Airtable Env

Use Airtable to host your Environment Variables.

## Usage

```
eval $(airtable-env <api-key> <base-key> <table> <view> <key-field> <value-field>)
```

 - key-field is the field holding the key name
 - value-field is teh field holding the value name

## Why?

There are many benefits to using Airtable to store secrets:

 - Pretty good ACL
 - Changelog and Comments List
 - Easy to update
 - Free Plan is Great


# Release

```
cargo install cargo-release
cargo release
```