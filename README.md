Go task plugin to run Shell scripts.

*Notes:*
This is only for convenience since you can run all commands directly through Go anyway.

This could be preferable because:
- Its exactly like shell script. Go's custom command takes a little getting used to.
- Its easier to CRUD commands since its a script, specially re-order them if required.

It should not be used as a replacement for important scripts like deployment scripts. They should remain in your repository.

*Usage:*
Download dist/script-executor-task-0.1.jar or from releases & place it in <go-server-location>/plugins/external & restart Go Server.