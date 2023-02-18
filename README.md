# A Condition Variable for Tokio

[![license-badge](https://img.shields.io/crates/l/tokio-condvar)](https://github.com/kaimast/tokio-condvar-rs/blob/main/LICENSE)
[![crates-badge](https://img.shields.io/crates/v/tokio-condvar)](https://crates.io/crates/tokio-condvar)

**Not Cancellation-Safe:** If your future gets canceled while inside wait, no other future may get woken up.

This is not part of the Tokio project.
See the discussion [here](https://github.com/tokio-rs/tokio/issues/3892) on why Tokio does not have a built-in Condvar implementation (yet).
