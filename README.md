# SmartCrop

A work in progress WordPress plugin that adjusts the crop location of cropped thumbnail images so that the theoretically most interesting part of the image is shown instead of only the center.

Analysis is done asynchronously after upload to prevent slow upload processing. This means that your browser may cache the centered verson before it's later overwritten with the smartly cropped version.

Image analysis is based on code by @gschoppe.