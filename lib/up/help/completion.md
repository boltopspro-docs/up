<!-- note marker start -->
**NOTE**: This repo contains only the documentation for the private BoltsOps Pro repo code.
Original file: https://github.com/boltopspro/up/blob/master/lib/up/help/completion.md
The docs are publish so they are available for interested customers.
For access to the source code, you must be a paying BoltOps Pro subscriber.
If are interested, you can contact us at contact@boltops.com or https://www.boltops.com

<!-- note marker end -->

## Examples

    up completion

Prints words for TAB auto-completion.

    up completion
    up completion hello
    up completion hello name

To enable, TAB auto-completion add the following to your profile:

    eval $(up completion_script)

Auto-completion example usage:

    up [TAB]
    up hello [TAB]
    up hello name [TAB]
    up hello name --[TAB]
