# Code Review Guideline

The purpose of code review is to improve the quality of the codebase, ensure that coding standards are being followed, and provide feedback and guidance to team members.

<hr>

## Process

 - Peer review is required from at least one other team member before merging. The peer reviewer should be selected based on their expertise and experience in the relevant area of the codebase.
 - The software architect may also be required to review from time to time to ensure that the codebase is meeting agreed-upon standards and guidelines. The software architect should be added to each pull request (PR) as a reviewer.
 - All team members should review PRs in a timely manner, and provide constructive feedback and guidance to the author.
 - PRs should be kept open for a maximum of 2 days, after which they will be automatically closed if not merged.
 - The software architect is responsible for merging PRs to the dev or main branches and keeping track of rejected and accepted PRs.
 - If a PR is rejected, the author should address the issues raised and resubmit the PR for review.

<hr>

## Branch naming

We have three primary branch categories
<ul>
    <li><strong>feature</strong>: For new features. Sample: <i>feature/hmo-plans</i> </li>
    <li><strong>updates</strong>: For updates on an existing feature. Sample: <i>update/doctor-data</i></li>
    <li><strong>fix</strong>: For bug fixes to an existing feature. Sample: <i>fix/consultation-time</i></li>
</ul>

<hr>

## Reviews and merge strategy

<ol>
    <li>Create your local branch following the branch naming scheme</li>
    <li>Make changes</li>
    <li>Push changes</li>
    <li>Request reviews and get at least one approval</li>
    <li>Discuss on the PR and make changes if necessary</li>
    <li>Merge to <strong>staging</strong> if you get at least one approval </li>
</ol>

## Standards

 - Code should be well-documented, easy to read, and maintainable.
 - Code should be tested and free of errors before being submitted for review.
 - Code should follow the agreed-upon coding standards and guidelines.
 - PRs should include a clear and concise description of the changes being made, including any relevant context or background information.
 - PRs should include any necessary test cases or documentation to support the changes being made.
 - PRs should be reviewed for security, performance, and scalability concerns.
 - PRs should be reviewed for compliance with legal and regulatory requirements, as applicable.
