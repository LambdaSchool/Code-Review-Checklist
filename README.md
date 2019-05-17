# Lambda School Daily Code Review Checklist

Code review is the time to catch issues and help students who don't understand concepts from the day or week. A thorough code review may take between 20-30 minutes, but you can do a condensed code review in under 15 minutes, especially if you batch them together and boost your efficiency. Instructors, PMs, or peer mentors can use the code review as an opportunity to push and challenge students technically. 
While students should feel free to ask questions, they should also be ready to explain and defend your code.

## Part I - Review Projects

Review each project, including assignments, personal projects, or Sprint Challenges since the last code review. At a minimum, review the code for the following:

1. Each project is pushed to GitHub with clear, detailed commit messages.
2. Each project is feature complete and works as expected.
3. There are no exceptions or warnings in your console or Chrome Developer Tools.
4. Code follows consistent naming conventions, language idioms, and style.
5. Code is written by the student.

## Part II - Review Objectives

Objectives from the Training Kit are written in our 'Student can...' format, and reflect the skills the student will have demonstrated in their project, assignment, or sprint challenge. Using the student's tracker, review each competency or objective in each sample of code, and determine a rating (0-3) on each one.

Ask to see examples of each objective in the project. Ask the student to explain the code and how it demonstrates their mastery.

#### Rating Scale

| Score | Description |
| :-- | :-- |
| 0       				| Not observable |
| 1       				| Does not understand, does not meet expectations |
| 2 <sup>*</sup>  | Understands with assistance, meets expectations |
| 3       				| Understands independently, exceeds expectations |

<sup>*</sup> `2` is the default score. A `3` should only be awarded when the student has demonstrably mastered the objective.

##### NOTE: Ratings are not grades, and there are no GPAs. Students and reviewers should come to a consensus rating to understand where the student excels, and where the student may need some extra attention or help.

## Part III - Review Past Objectives

Choose a handful of previous objectives to review or discuss. If the code review is happening in a peer mentoring setting, this will likely happen with one student reviewing another's code.

Focus on objectives where the student did not meet expectations. If the student has reviewed and improved, update the score. Otherwise, address the concerns in this step, or when making a plan.

## Part IV - Make a Plan

Make a plan. Focus on fixing deficiencies first, then focus on mastery, stretch goals, or other advanced work.

Plans should include videos, resources, or exercises the student will complete in order to improve their mastery.

## Part V - Address Any Additional Needs

If there are any specific needs or concerns with the student, share them with a PM or Instructor.

## Part VI - Student Pull Request Feedback Template

```markdown
## Great

## Requested Improvements

## Questions

## Rating: {1-3}

#### GitHub Contribution Graph
```

## Part VII - GitHub Contribution Graph

![Heat Map](img/contribution-graph-heat-map.png)

### UPDATE

We recommend against de-forking while in class - just so all the links submitted stay active. But, you don't really need to de-fork anything.

All the commit history lives in the `.git` folder in the local Git repo directory - you just need to get the project up to GitHub. This can be as simple as:

1. creating a new repo on GitHub,
2. giving it a unique name to help distinguish it in your GitHub repository list, and
3. pushing the project up to the new GitHub repository.

It might help to make a "Team" to keep the "active student" repositories separate from the ones pushed up for the heatmap.

Lambda School's 2019 [Git branching workflow](https://youtu.be/cSoHP7WSsEg) will result in contributions reflected in your GitHub heatmap.

Latest update: 2/8/2019

***

<details><summary>The following is deprecated</summary><p>

Unfortunately, commits made in a fork are not counted towards the contribution graph on your GitHub profile. Please see the "[Commit was made in a fork](https://help.github.com/articles/why-are-my-contributions-not-showing-up-on-my-profile/#commit-was-made-in-a-fork)" section of GitHub's _"Why are my contributions not showing up on my profile?"_ article:
> Commits made in a fork will not count toward your contributions. To make them count, you must do one of the following:
> 
> 1. Open a pull request to have your changes merged into the parent repository.
> 2. To detach the fork and turn it into a standalone repository on GitHub, contact [GitHub Support](https://github.com/contact). If the fork has forks of its own, let support know if the forks should move with your repository into a new network or remain in the current network. For more information, see "[About forks](https://help.github.com/articles/about-forks/)."

Option one is not available to Lambda School students. With option two, you should find that GitHub Support is very friendly and timely with their response. You can, however, get your "Heat Map" to accurately reflect your contributions another way. Please visit [this repository](https://github.com/LambdaSchool/GitHub-Contribution-Graph). You will find detailed instructions on how to "de-fork" your repositories. :octocat:

</p></details>
