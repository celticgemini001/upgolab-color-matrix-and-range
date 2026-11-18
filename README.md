# Colour Matrix and Range Before Upscaling: Two Bugs That Look Identical, Measured

A bt709/bt601 matrix mismatch and a limited/full range mismatch both tint your output. Measured against a known reference: the same bug costs 0.02 dB on mid-tones and 16 dB on saturated colour, upscaling passes the error through untouched, and a neutral ramp tells you which of the two you actually have in three lines.

**Read it with the tables and the reproduction snippets:** <https://celticgemini001.github.io/upgolab-color-matrix-and-range/>

## About this repo

This repository exists to serve one measured article. Every number in it came from
ffmpeg and numpy run on real files on this machine — the commands are in the page so
you can re-run them and get the same rows. Where the measurement contradicted the
hypothesis, the page says so.

## The tool behind the notes

<https://upgolab.com> — browser-based AI upscaler for photos and short video.

## Index

All the guides are cross-linked from the hub:
<https://celticgemini001.github.io/upgolab-tools/>
