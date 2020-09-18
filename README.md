# Gesture Recognisers in iOS

This repo contains the markdown, slides, scripts, and other elements that were formerly in `For instructors` directory.

Any resources and starter kit can be found in [Instructor Resources Repo](https://github.com/raywenderlich/vdd-resources).

Helpful step-by-step instructions for creating your course can be found: [Core Course Instructor Guide](https://guides.raywenderlich.com/core-course-instructor-guide) or [Spotlight Course Instructor Guide](https://guides.raywenderlich.com/spotlight-course-instructor-guide).


> __NB:__ The downloadable materials, previously `For Students` directory, that accompany the video (source code, projects etc) must __not__ be stored in this repo. They should
> be stored in a separate repo, here: [https://github.com/raywenderlich/video-gri-materials](https://github.com/raywenderlich/video-gri-materials).


## How to create a new edition

Major new releases should be created thusly:

1. Create a new branch off the latest `versions/x.x` branch, with the new
version number. For example, if your latest published edition is `versions/1.2`,
 one would branch off `versions/1.2` to create the `versions/2.0` version.
2. Set the new branch as the default branch in Settings. This will ensure that
   people arriving to the site, or anyone cloning the repository, will be shown
    the branch that is currently in progress.
3. Repeat this process in the associated materials repo.
4. Update __release.yaml__ with any changes. As a minimum, the following fields
   will require an update to reflect the new version details:
   - `version`
   - `version_description`
   - `materials_url`
5. Create any branches you desire off the new branch.
