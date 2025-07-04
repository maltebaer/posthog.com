---
title: Send PostHog event data to Knock
templateId:
    - template-knock
---

import Requirements from "../_snippets/requirements.mdx"
import FeedbackQuestions from "../_snippets/feedback-questions.mdx"
import PostHogMaintained from "../_snippets/posthog-maintained.mdx"

<Requirements />

You'll also need access to the relevant Knock account.

## Installation

1. In PostHog, click the [Data pipeline](https://us.posthog.com/pipeline/overview) tab in the left sidebar.
2. Click the [Destinations](https://us.posthog.com/pipeline/destinations?search=knock) tab.
3. Search for **Knock** and click **+ Create**.
4. Add your Knock.app webhook destination URL at the configuration step.
5. Press **Create & Enable** and watch your 'Audience' list get populated in Knock!

<HideOnCDPIndex>

## Configuration

<TemplateParameters />

## FAQ

### Is the source code for this destination available?

PostHog is open-source and so are all the destination on the platform. The [source code](https://github.com/PostHog/posthog/blob/master/posthog/cdp/templates/knock/template_knock.py) is available on GitHub.

<PostHogMaintained />

<FeedbackQuestions />

</HideOnCDPIndex>