# A Condition Variable for Tokio

**Not Cancellation-Safe:** If your future gets cancelled inside wait, no other future may get woken up.

This is not part of the Tokio project.
See the discussion [here](https://github.com/tokio-rs/tokio/issues/3892) on why Tokio does not have a built-in Condvar implementation.
