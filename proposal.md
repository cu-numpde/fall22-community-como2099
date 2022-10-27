# Community Software Analysis Proposal
Please edit this file and push to your repository.

## Software: *PHASTA*

*Write a paragraph describing what the software does and who its
primary audience is.*

PHASTA stands for "Parallel Hierarchic Adaptive Stabilized Transient Analysis". It is a fluid solver that can solve both the compressible and the incompressible Navier Stokes equations. The incompressible case includes the equations for conservation of mass and momentum. For the compressible case, it solves conservation of energy in addition to mass and momentum. The solver is also equipped to simulate turbulence. The default turbulence model the solver uses is the RANS Spalart-Allmaras one-equation model, but it is equipped with other turbulence models as well. The primary audience of this software are university research groups that either modify the code in order to advance methods of CFD or run the code in order to solve novel physics problems. While the audience of this research code is relatively small compared to other open source projects, the groups who do interact with PHASTA keep the project alive and well. In addition to the public GitHub repository "PHASTA/phasta", there is a private repository called "PHASTA/phasta-next". The phasta-next repo is where new code ideas are introduced by the main developers. Once these ideas are fully fleshed-out, debugged and tested, they are then pushed to the public repo which is accessible by anyone. Any GitHub user is able to suggest changes to the public branch of PHASTA for review by the developers, but that is not the main way the code gets updated.

### Stats

| Description | Your answer |
|---------|-----------|
| Repository URL | https://github.com/PHASTA/phasta |
| Main/documentation website | https://fluid.colorado.edu/wiki/index.php/Main_Page |
| Year project was started | 1991 |
| Number of contributors in the past year | 3 |
| Number of contributors in the lifetime of the project | 9 listed on GitHub, many more not listed |
| Number of distinct affiliations | ~5 |
| Where do development discussions take place? | Slack |
| Typical number of emails/comments per week? | 20 |
| Typical number of commits per week? | once every couple of months for the public repo, twice a week for the private repo |
| Typical commit size | ~2 files changed, ~20 insertions, ~20 deletions |
| How does the project accept contributions? | pull requests  |
| Does the project have an automated test suite? | no |
| Does the project use continuous integration? | yes |
| Are any legal/licensing steps required to contribute? | no |

### Install and run

Check the following boxes when complete or add a note below if you
encountered a problem.

- [ Y ] I have installed the software
- [ Y ] I have run at least one example
- [ N/A ] I have run the test suite
- [ N/A ] The test suite passes
	- potential project could be adding a test suite

### Notes/concerns/risks

Please comment on any anomalies or known risks to following this
project, if you were unable to answer any questions above, or
otherwise have concerns about the appropriateness of the software.  If
the project requires a contributor license agreement or other
procedural steps, please explain here.  "None at this time" is
acceptable for this question.

I currently use and develop PHASTA for my research and it will likely be a cornerstone for my thesis. I recognize the project is pretty small and that major developments don't happen in the open-source community, so if it is ultimately a poor choice for this class's project I understand. However, I think doing the project in PHASTA would be beneficial for me because it would help me become familiar with the GitHub side of the project and also potentially help advance my research. If you think PHASTA could be acceptable to move forward with, I can talk to Ken to come up with ideas for a project that would be suitable for this class as well as my own research.

#### Note on copyright
Students retain copyright on any work done in completion of a CU
course, so you are authorized to sign a [contributor license
agreement (CLA)](https://en.wikipedia.org/wiki/Contributor_License_Agreement),
affirm a [developer's certificate of
origin (DCO)](https://en.wikipedia.org/wiki/Developer_Certificate_of_Origin),
etc.  If you have concerns about this, please note them and/or reach
out to Jed directly.
