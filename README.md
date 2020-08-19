# 2020-09-talk-pytest

A ten minute talk on pytest. With time for questions.

Audience: people who have done at least a small amount of Python coding.
I do not expect you to have written tests or used testing tools.

## What is pytest?

See https://docs.pytest.org/en/latest/

## How do I install pytest?

With `conda`:

    conda create --name pytest-talk pytest
    
With plain old virtualenv:

    python -m venv pytest-demo
    . pytest-demo/bin/activate
    pip install pytest
    
In a project that has already been setup with
some basic level of package management,
you might find that it already has a system for installing dependencies and tools.

## Why should I use pytest?

## How do I use pytest?

    pytest
    
How do I use pytest in Visual Studio Code?

## What are the alternatives?

`unittest`, `hypothesis`, `doctest`, and the older `nosetest`.

Also, may be embedded in a larger scope framework like `tox`
