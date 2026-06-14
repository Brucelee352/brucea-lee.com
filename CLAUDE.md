# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is a single-page static website (`brucea-lee.com`) hosted via GitHub Pages. It serves as a portfolio landing page that is meant to land users to other projects within the domain brucea-lee.com. The webpage is also meant to be sparse, minimalistic and coded as a basic react file that uses rounded button with a light-indigo color scheme. 

## Structure

- `index.html` — the entire site. Features subdomains with projects brucea-lee.com/mh and brucea-lee.com/underempoyment respectively, with flexibility to add more projects to link to this page in the future. The domain is hosted in spaceship. 
- `CNAME` — GitHub Pages custom domain: `brucea-lee.com` or `https://brucea-lee.com/` 

## Deployment

Changes pushed to `main` are automatically deployed via GitHub Pages. There is no build step — the site is a basic react file.

## Python Dash apps

The portfolio apps that are being hosted are completely separate codebases from this front-facing website, they are Python Dash apps that run from a Google Cloud Run hosted container and loaded upon vistation to the website. 