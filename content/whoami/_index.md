+++
title = "whoami" # title of the page
description = "visit to know me."
layout = "whoami" # sets the layout to use
noindex = false # tell robots not to index
[security.csp.directives]
  scriptSrc = [
    "'sha512-6G7cmlXR4eLBphfUmmEWLEnLWSEtZPdKP2xv7bXZ8D3LReZazwxcwb4tTx2HeCeoAChG5ZCE+UqHmbe3K4xoJg=='",
    "'unsafe-eval'"
  ]
+++
