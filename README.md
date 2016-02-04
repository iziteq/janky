# How to setup a new repository

curl -v -X POST -F nwo=<repository name with owner> -F name=<jenkins job name> -F template=<template name> http://login:password@localhost:3000/_hubot/setup

Run this command locally on jenkins@ops.izi.travel

Example:

curl -v -X POST -F nwo=iziteq/izi-cms -F name=CMS -F template=cms http://hubot:secret@localhost:3000/_hubot/setup
