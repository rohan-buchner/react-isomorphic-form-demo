# Demo app for [react-isomorphic-form]

This is an example app using [react-isomorphic-form] with React Router. It
demonstrates how react-isomorphic-form can render server-side and be enhanced
client-side.

The client-side JavaScript is intentionally slow to load (it's recompiled on
each request) in order to demonstrate the form's functionality while loading.
You should be able to input data while the page is still loading, and the form
should retain those values when JavaScript kicks in.<sup id="a1">[1](#f1)</sup>

<sup id="f1">[1](#a1)</sup> Due to an issue in React, this doesn't work for
textareas.

[react-isomorphic-form]: https://github.com/ghengeveld/react-isomorphic-form

## Live demo

👉 http://react-isomorphic-form-demo.herokuapp.com/

The live demo might be slow to initially boot as it runs on a free Heroku Dyno
which goes to sleep after 30 minutes of inactivity.

## Running locally

```shell
npm install
npm start
```

It should now be running at [http://localhost:8000](http://localhost:8000).
