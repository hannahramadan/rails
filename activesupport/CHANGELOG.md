*   Add instrumentation for ActionController::Live#send_stream

    Allows subscribing to `send_stream` events. The event payload contains the filename, disposition, and type.

    *Hannah Ramadan*

*   Use Ruby 3.3 Range#overlap? if available

Please check [7-1-stable](https://github.com/rails/rails/blob/7-1-stable/activesupport/CHANGELOG.md) for previous changes.
