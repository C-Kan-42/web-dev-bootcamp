# Welcome to the Modern Web Dev Boot Camp

## Prerequisites

- Create a [GitHub account](https://github.com)
- Install, on your own computer:
  - [VS Code](https://code.visualstudio.com/download)
  - [Node.js](https://nodejs.org/en/download)
  - [Slack](https://slack.com/downloads/)

## Tutorial Outline

<table>
  <thead>
    <tr>
      <th>Time</th>
      <th>Location</th>
      <th>Topic</th>
    </tr>
  </thead>
  <tbody>
    <tr><td colspan="3">Monday, August 14, 2023</td></tr>
    <tr><td>TBD</td><td>TBD</td><td><a href="syllabus/git-lecture.md">Git Lecture</a></td>
    <tr><td>TBD</td><td>TBD</td><td><a href="syllabus/git-exercise.md">Git Exercise</a></td>
    <tr><td>TBD</td><td>TBD</td><td><a href="syllabus/modern-javascript.md">Modern JavaScript Lecture</a></td>
    <tr><td>TBD</td><td>TBD</td><td><a href="syllabus/web-dev-exercise.md">Web Dev Exercise</a></td>
    <tr><td colspan="3">Monday, August 15, 2023</td></tr>
    <tr><td>TBD</td><td>TBD</td><td><a href="syllabus/cloud-basics-lecture.md">Cloud Basics Lecture</a></td>
    <tr><td>TBD</td><td>TBD</td><td><a href="syllabus/tutorial-walkthrough.md">Tutorial Walkthrough</a></td>
  </tbody>
</table>

## Development

The following command will run two processes during development when using Architect as your server.

- Your Architect server sandbox
- The Remix development server

```sh
$ npm run dev
```

Your file changes are watched, and assets are rebuilt upon change.

Open up [http://localhost:3333](http://localhost:3333) and you should be ready to go!

## Deploying

Before you can deploy, you'll need to do some setup with AWS:

- First [install the AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html)
- Then [follow the Architect setup instructions](https://arc.codes/docs/en/guides/get-started/detailed-aws-setup).

If you make it through all of that, you're ready to deploy!

1. build the app for production:

   ```sh
   npm run build
   ```

2. Deploy with `arc`

   ```sh
   arc deploy production
   ```

You're in business!
