---
layout: page
title: Use PlanetLab
nav_order: 2
---
# Using PlanetLab

We at PlanetLab welcome researchers from around the world to run experiments on our nodes.

## Become a user

Anyone can create a PlanetLab account, just [go to the console](https://console.planetlab.io/), register, and agree to the acceptable use policy.

To use your account to deploy containerized software to the nodes, you need approval, which can be obtained in one of two ways:

- from an existing user in a position of responsibility who knows you and can vouch for you; ask to join their team and/or one of their workspaces via the console
- from PlanetLab management; if you are in a position of authority (e.g., professor or manager) at your institution, ask to create a team

Please provide an institutional e-mail address when registering.

Users of the European Union's [SLICES-RI portal](https://portal.slices-ri.eu/) who have been approved there are automatically authorized to use PlanetLab, and simply need to authenticate via the "Login with Slices" button on our console.

## Create a team

PlanetLab welcomes university professors, instructors who wish to use the platform for laboratory exercises for their classes, researchers from not-for-profit research institutions, and memebrs of public and industry research laboratories. Industry use is limited to pre-commercial purposes.

If you are in one of these categories and would like access to PlanetLab for yourself and others with whom you work, become a PlanetLab user and, within the console, request the creation of a team. PlanetLab administrators will verify the information that you provide. Once approved, you will be able to ask people to become users of your team, approve or reject team membership requests, and and manage workspaces (see below).

As a team manager, you do _not_ need to be familiar with Docker or Kubernetes. You can manage your team via entirely via the web console.

## Deploy via a workspace

All work is done in workspaces that are created via the console. These correspond to Kubernetes namespaces, and users make use of the familiar `kubectl` command-line tool and YAML configuration files to deploy and manage their containerized software.
