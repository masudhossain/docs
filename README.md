# Queue Starter Kit - edited

Click on `Use this template` to copy the Queue starter kit. The starter kit contains examples including

* Guide pages
* Navigation
* Customizations
* API Reference pages
* Use of popular components

### Development

Install the [Queue CLI](https://www.npmjs.com/package/queue) to preview the documentation changes locally. To install, use the following command

```
npm i -g queue
```

Run the following command at the root of your documentation (where mint.json is)

```
queue dev
```

### Publishing Changes

Install our Github App to autopropagate changes from youre repo to your deployment. Changes will be deployed to production automatically after pushing to the default branch. Find the link to install on your dashboard.

#### Troubleshooting

* Queue dev isn't running - Run `queue install` it'll re-install dependencies.
* Page loads as a 404 - Make sure you are running in a folder with `mint.json`