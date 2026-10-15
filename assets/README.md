# Learning-route decoration

These original diagrams are generated from project-authored drawing code in
`generate-route.py`. No external artwork, model-generated image, secret, or learner
data is used. Project asset licensing remains an owner decision before publication.

- `learning-route.svg`: static, default route diagram with title, description,
  visible text, no scripts, no animation, and no external references.
- `learning-route.gif`: optional decorative dot moving along the same route. It
  runs once for 2.4 seconds, with 24 frames and no looping extension or flashing.

Each chapter keeps the static SVG and equivalent text visible by default. The GIF
is inside a native collapsed disclosure. GitHub may load an image while a disclosure
is closed; the GIF might have finished before it is opened. GitHub cannot apply OS
reduced-motion settings to GIFs. The static image and text convey the full meaning;
there is no instruction to enable motion or replay it to complete an exercise.

Regenerate only when Pillow is already available; do not install automatically:

```sh
python3 courses/full-stack-modern-react-nextjs/assets/generate-route.py
python3 courses/full-stack-modern-react-nextjs/assets/generate-route.py --check
```

Rendering details may vary with Pillow's bundled default font. The checker verifies
size, frame count, duration, and absence of a looping extension.
