# Community plugins

We created this repository in 2016 to accept plugin submissions from the Grafana community. 5 years and more than 150 published plugins later, it's clear that community plugins have been instrumental in the success of Grafana. We'd like to make the process of submitting plugins even easier.

We're excited to announce that you can now [submit your plugin](#submit-your-plugin) and [maintain your plugin](#maintain-your-plugin) directly from your Grafana Cloud account!

This also means that we're starting the process of deprecating this repository. Here's how it'll affect you:

- If your pull request has been triaged by us already and is waiting for review, you don't need to do anything. We'll continue to review the remaining plugin submissions in the pipeline.
- If you'd like, you can migrate your current plugin submission by submitting it through the new submission flow. Let us know that you'd like to use the new flow by updating your pull request. Please keep the pull request open to keep your position in the review queue.
- If you're submitting a new plugin or an update to an existing plugin, please use the new submission flow. We won't accept any new plugin submissions on this repository.

If you have any questions, [create a new issue](https://github.com/grafana/grafana-plugin-repository/issues/new), or send an email to  `plugin-reviews@grafana.com`.

## Submit your plugin

Before you submit your plugin, we ask that you read our [Guidelines](#guidelines) and [Frequently Asked Questions](#faq).

1. [Log in](https://grafana.com/auth/sign-in) to your Grafana Cloud account.
1. In the left menu, click **My Plugins** under **Org settings**.
1. Click **Submit Plugin**.
1. Enter the information requested by the form.
	- **OS & Architecture:** 
		- Select **Single** if your plugin archive contains binaries for multiple architectures.
		- Select **Multiple** if you'd like to submit separate plugin archives for each architecture. This can lead to faster downloads since users can select the specific architecture they want to install the plugin on.
	- **URL:** A URL that points to a ZIP archive of your packaged plugin.
	- **MD5:** The MD5 hash of the plugin specified by the **URL**.
	- The remaining questions help us determine the [signature level](https://grafana.com/docs/grafana/latest/plugins/plugin-signatures/#plugin-signature-levels) for your plugin.
1. Click **Submit**.

<img width="808" alt="Screenshot 2021-08-25 at 12 31 32@2x" src="https://user-images.githubusercontent.com/8396880/130775117-b7839641-b418-4ae8-8a25-16f7a4929599.png">

## Maintain your plugin

To submit an update for an already published plugin:

1. [Log in](https://grafana.com/auth/sign-in) to your Grafana Cloud account.
1. In the left menu, click **My Plugins** under **Org settings**.
1. Click **Submit Update** for the plugin you want to update.
1. Enter the information requested by the form.
	- **OS & Architecture:** 
		- Select **Single** if your plugin archive contains binaries for multiple architectures.
		- Select **Multiple** if you'd like to submit separate plugin archives for each architecture. This can lead to faster downloads since users can select the specific architecture they want to install the plugin on.
	- **URL:** A URL that points to a ZIP archive of your packaged plugin.
	- **MD5:** The MD5 hash of the plugin specified by the **URL**.
1. Click **Submit**.

## Guidelines

To speed up the time it takes to review your plugin:

- Check that your plugin is ready for review using the [plugin validator](https://plugin-validator.grafana.net).
- Read our [6 tips for improving your Grafana plugin before you publish](https://grafana.com/blog/2021/01/21/6-tips-for-improving-your-grafana-plugin-before-you-publish/)

## FAQ

- **Do I need to submit a private plugin?:** No. Please only submit plugins that you wish to make publicly available for the Grafana community.
