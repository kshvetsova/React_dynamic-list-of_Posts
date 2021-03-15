# React dynamic list of Posts

Implement the app to manage post comments.

You are given a basic markup and [the API](https://mate-academy.github.io/fe-students-api/).
Use React Hooks instead.

1. Create an `/src/api/posts.js` and add a method `getUserPosts(userId)` there
1. Load posts and show them using the `PostsList` on page load. (use `useEffect` as a `componentDidMount`)
1. Implement the UserSelect to show only the posts of the selected user. (call `getUserPosts` each time when user changes)
1. Each post has an `Open` button that sets a `selectedPostId` in the `App`.
1. After opening the details the `Open` button becomes `Close` and will close the details onclick.
1. `PostDetails` component should be shown only after selecting a post.
1. Create `getPostDetails(postId)` method in `/src/api/posts.js` and load post details from `/posts/:postId`
1. Create `getPostComments(postId)` method in `/src/api/comments.js`, load comments from `/comments` and filter them using a given `postId`
1. Add a button to `show`/`hide` comments.
1. Add an `X` button near each comment to delete it on the server.
1. Add a form to add a new comment to the current post
1. Comments should be immediately updated after adding or removing.

Tech stack:
- HTML5, CSS3, JavaScript, React, Hooks, Fetch, API

   [DEMO LINK](https://kshvetsova.github.io/Dynamic_list_of_posts/)

