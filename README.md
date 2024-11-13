# Hello world docker action

This repository is a sandbox to learn how to GitHub Actions with Docker containers by
following [this tutorial](https://docs.github.com/en/actions/sharing-automations/creating-actions/creating-a-docker-container-action)

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

## `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

## `time`

The time we greeted you.

## Example usage

uses: actions/docker-container-action@v2
with:
    who-to-greet: 'Mona the Octocat'