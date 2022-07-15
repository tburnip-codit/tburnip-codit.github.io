# Jekyll

This page is using the Jekyll slate theme that is selected in [repository settings](https://github.com/tburnip-codit/tburnip-codit.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

# Mermaid
```mermaid
  flowchart TD;
      A[Receive  file] --> B{Valid file?};
      B-- Yes --> C[Process file]-->D[Send Processed Message];
      B-- No --> E[Send Error Message];
     
