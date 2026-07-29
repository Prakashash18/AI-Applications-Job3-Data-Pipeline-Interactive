# Teacher Guide — Job 3 Data Pipeline + CNN Diagnosis

## Audience
ITE vocational students learning AI Applications with basic Python exposure.

## Teaching aim
Move from concrete demos to code. Students should be able to explain what happens from URL download to CNN training and diagnosis.

## Suggested flow

### Act 1 — Data comes from somewhere
Slides 1–10 introduce imports, URLs, compressed `.tgz` files, `untar=True`, and paths.

Key phrases:
- Import = bring a tool into the script.
- URL = web address of the dataset file.
- Untar = unpack a compressed parcel.
- Path = address of a file or folder on the computer.

### Act 2 — Folders become datasets
Slides 11–17 show class folders, image size, batch size, training/validation split, and previewing images.

Ask repeatedly:
- Which data teaches the model?
- Which data checks the model?

### Act 3 — Plotting code
Slides 16–17 teach the image preview code line by line. Slide 28 teaches training-curve plotting line by line.

### Act 4 — CNN layers
Slides 18–25 scaffold rescaling, filters, Conv2D, activation functions including ReLU and tanh, pooling, flatten, and dense layers.

### Act 5 — Model diagnosis
Slides 26–37 teach accuracy, loss, common ML algorithms, underfitting, overfitting, dropout, augmentation, and comparing curves.

### Act 6 — Prediction and handoff
Slides 38–44 explain prediction confidence, generalisation, quick checks, and practical steps.

## Recommended activities

- Let students click import tools and explain each in one sentence.
- Ask students to predict what `untar=True` does before opening the parcel.
- Use the ratio slider to compare 70/30, 80/20 and 90/10.
- Use the fit slider to ask: underfit, good fit or overfit?
- Use dropout helper animation to explain why dropout is training-only behaviour.

## Common misconceptions

- Validation data is not used to update weights.
- High training accuracy alone is not enough.
- Overfitting is not “a better model”; it is memorisation.
- Underfitting and overfitting require opposite fixes.
- Confidence is not a guarantee.
