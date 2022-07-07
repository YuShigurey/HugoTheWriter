---
title: "Rookie"
date: 2022-06-29T01:27:37+08:00
draft: true
---

# Chapter 2

cargo new project-name/ cargo init

## Add dependency

rand = "0.8.3"

update with `cargo update`

Ignore major version leap. Must do change dependecies' main version manually.


## Generate a document/ Read dependencies document.

cargo doc --open

## Derive (at least for Debug and struct)

`#[derive(Debug)]`

## Other

create array with
`let myar: [type; size] = [...];`
