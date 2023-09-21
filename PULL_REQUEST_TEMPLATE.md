<!--
  For Work In Progress Pull Requests, please use the Draft PR feature,
  see https://github.blog/2019-02-14-introducing-draft-pull-requests/ for further details.
  
  For a timely review/response, please avoid force-pushing additional
  commits if your PR already received reviews or comments.
  
  Before submitting a Pull Request, please ensure you've done the following:
  - 👷‍♀️ Create small PRs. In most cases, this will be possible.
  - ✅ Provide tests for your changes.
  - 📝 Use descriptive commit messages.
  - 📗 Update any related documentation and include any relevant screenshots.
-->

## What type of PR is this? (check all applicable)

- [ ] 🍕 Feature
- [ ] 🐛 Bug Fix
- [ ] 📝 Documentation Update
- [ ] 🎨 Style
- [ ] 💻 Code Refactor
- [ ] 🔥 Performance Improvements
- [ ] ✅ Test
- [ ] 🤖 Build
- [ ] 🔁 CI
- [ ] 🔌 Chore (Release)
- [ ] ⏩ Revert

## Description

<!-- 
Please do not leave this blank 
This PR [adds/removes/fixes/replaces] the [feature/bug/etc]. 
-->

## Related Issues
<!-- 
Please use this format link issue numbers: Fixes #123
https://docs.github.com/en/free-pro-team@latest/github/managing-your-work-on-github/linking-a-pull-request-to-an-issue#linking-a-pull-request-to-an-issue-using-a-keyword 
-->

## Mobile & Desktop Screenshots/Recordings

<!-- Visual changes require screenshots -->


## Added tests?

- [ ] 👍 yes
- [ ] 🙅 no, because they aren't needed
- [ ] 🙋 no, because I need help

## Added to documentation?

- [ ] 📜 README.md
- [ ] 📓 docs.komiser.io
- [ ] 📕 storybook
- [ ] 🗒 Code comment intelliSense
- [ ] 🙅 no documentation needed

## Complete the checklist before considering this PR as "Ready to review"

- [ ] Pull the Code - Ensure the functionality works locally.
- [ ] Compare to the Design - Check if everything matches the design specifications. Validate the consistency of colors, fonts, paddings, etc.
- [ ] Responsive Testing - Resize the browser window to ensure nothing breaks on mobile
- [ ] Code Quality - Ensure best coding practices are used \*
- [ ] Ensure no commented-out code or debug logs are left behind.
- [ ] Check for code modularity and reusability.
- [ ] Check for descriptive variable names: e.g., "totalPrice" not "tp".
- [ ] Ensure there are no linting errors `npm run lint`
- [ ] Ensure the code passes the build `npm run build`
- [ ] Ensure there are no inline error disabling/ignores
- [ ] Ensure all newly added dependencies are actually necessary (package.json)
- [ ] Check that the PR has a title and description

*React specific:*
```
Key Prop: e.g., "Unique key prop given to all elements in a list."
Prop Drilling: e.g., "Avoid excessive prop drilling; consider context or state management."
Effect Dependencies: e.g., "All dependencies added in useEffect dependency array."
Custom Hooks: e.g., "Logic extracted to custom hooks for reusability."
Memoization: e.g., "Used React.memo, useMemo for expensive computations."
Provider Placement: e.g., "Providers wrap necessary components only."
Semantic JSX: e.g., "Used <button> for buttons, not <div>."
```

## [optional] Are there any post-deployment tasks we need to perform?

None

## [optional] What gif best describes this PR or how it makes you feel?

You can use [Gif for GitHub](https://chrome.google.com/webstore/detail/gifs-for-github/dkgjnpbipbdaoaadbdhpiokaemhlphep/related?hl=en) extension to generate one
