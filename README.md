# Gesture Recognisers in iOS

This production repo contains the markdown, slides, scripts, and other elements to support the creation of the above video course.

Any resources needed can be found in the [Instructor Resources Repo](https://github.com/raywenderlich/vdd-resources).

Helpful step-by-step instructions for creating your course can be found in the [Core Course Instructor Guide](https://guides.raywenderlich.com/core-course-instructor-guide) or the [Spotlight Course Instructor Guide](https://guides.raywenderlich.com/spotlight-course-instructor-guide).


> __NB:__ The downloadable student materials, previously inside the `Student Materials` or `For Students` directory, are __not__ be stored in this repo. They are
> stored in a separate repo, here: [https://github.com/raywenderlich/video-gri-materials](https://github.com/raywenderlich/video-gri-materials).


## How to create a new version/edition

New course versions should be created thusly:

1. Create a new branch off the latest `versions/x.x` branch with the new
version number. For example, if the latest published edition is `versions/1.2`,
 one would branch off `versions/1.2` to create the `versions/2.0` version.
2. Set the new branch as the default branch in Settings. This will ensure that
   people arriving to Github, or anyone cloning the repository, will be shown
    the branch that is currently in progress.
3. Repeat step #1 for the associated materials repo, but do NOT set the new branch as default, since that would update the student materials link before the updated course goes live. The video producer will set the new branch as default when the course releases.
4. Update __release.yaml__ with any changes. As a minimum, the following fields
   will require an update to reflect the new version details:
   - `version`
   - `version_description`
   - `materials_url`
5. Delete or update the old project, scripts, and slides.
6. Create any branches you desire off the new branch.
