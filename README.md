# Image Annotation Practice Tool

A simple browser tool to practice image annotation. No backend, no API key.

**Live demo:** https://github.com/mdshahedulislamsaim/image-annotation-practice-tool/

## What it does
- Upload an image and draw bounding boxes
- Label boxes: Person, Car, Bicycle, Dog, Cat
- Move, resize, relabel and delete boxes
- Quality checklist and automatic hints
- Review mode: score my boxes against a COCO reference file (IoU, missed, extra, wrong label)
- Second pass: compare my work with my own earlier pass to check consistency
- Export as practice JSON or COCO JSON
- Self-test panel that checks the scoring code against answers worked out by hand

## How to use
1. Open the live demo and upload an image.
2. Annotate it.
3. Load a COCO JSON file and press Start review.

## Built with
HTML, CSS and JavaScript in a single file.
