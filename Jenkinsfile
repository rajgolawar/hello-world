#!groovy

// ===============================================================
// Update variables in this section when changing Syapse versions
// ===============================================================

// To use a special branch of Apps
// simply use the same branch name as your custom branch.
// Otherwise we use this branch.
FALLBACK_BRANCH = 'develop'


// The source for this library is found at
// https://github.com/syapse/jenkins-pipeline-library/tree/dev_4.0
@Library('syapse@develop')
import syapse.Selector

new Selector(this).select().run()