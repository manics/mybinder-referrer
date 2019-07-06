# mybinder-referrer
Example of redirecting to mybinder based on the referrer header.

Include a link to https://www.manicstreetpreacher.co.uk/mybinder-referrer/ in your mybinder repository README.
The webpage will detect the referrer and generate a mybinder URL using client-side Javascript.
This means you do not need to construct a dedicated mybinder URL for every repository, and also means if a repository is forked the README mybinder link will automatically load the forked repository.

See https://github.com/manics/mybinder-referrer/tree/demo for an example.

Currently this only works for GitHub gists and GitHub repositories.
