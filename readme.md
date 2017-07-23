
# Crowdsourcing Image Annotations
In this tutorial, we are going to use Boto3, the AWS SDK for Python Version 3, to access the Amazon Mechanical Turk API. After installing the Boto SDK, we are going to use Boto3 for croudsourcing image annotations.

This first part shows how to use Boto to create HITs and retrieve results. 
Then, we are going to develop a project that can use MTurk to locate objects in images. We will create a Human Intelligence Task (HIT) that will ask Workers to draw a bounding box around specific objects. Once the HIT is submitted, the Requester will receive a set of coordinates corresponding to the points the Worker has labeled. This information will allow the Requester to have Workers locate objects in images, so that they can then help train machines to perform the same operation.

The Tutorial is split into four parts:

1. [Crowdsourcing Image Annotations - Part 1](crowdsourcing_image_annotation_part1.md)

2. [Crowdsourcing Image Annotations - Part 2](crowdsourcing_image_annotation_part2.md)

3. [Crowdsourcing Image Annotations - Part 3](crowdsourcing_image_annotation_part3.md)

4. [Crowdsourcing Image Annotations - Part 4](crowdsourcing_image_annotation_part4.md)

I have developed these tutorials by migrating previous Amazon tutorials for Boto2 and changing the code and steps as needed, specifically:

- [Tutorial: Getting started with MTurk and Python using Boto](https://blog.mturk.com/tutorial-getting-started-with-mturk-and-python-using-boto-452fb0243a30#.eggez6xwf)

- [Tutorial: Using the MTurk Requester Website together with Python and Boto](https://blog.mturk.com/tutorial-using-the-mturk-requester-website-together-with-python-and-boto-4a7ef0264b7e#.7uz9w4hov)

- [Tutorial: Annotating images with bounding boxes using Amazon Mechanical Turk](https://blog.mturk.com/tutorial-annotating-images-with-bounding-boxes-using-amazon-mechanical-turk-42ab71e5068a#.z0clf9aln)

- [Tutorial: Retrieving bounding box image annotations from MTurk](https://blog.mturk.com/tutorial-retrieving-bounding-box-image-annotations-from-mturk-253b86cb7502#.obytdqw01)

- [Tutorial: Measuring the accuracy of bounding box image annotations from MTurk](https://blog.mturk.com/tutorial-measuring-the-accuracy-of-bounding-box-image-annotations-from-mturk-ad3dfcdf8aa0#.m2fm7ad1q)

- [MTurk Code Samples Python](https://github.com/awslabs/mturk-code-samples/tree/master/Python)
