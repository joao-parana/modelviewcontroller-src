# Variations on the notification strategy

   * [Qualified Notification Model](02_mvc_variations/05_qualified_notification_model): Deliver notification with enhanced semantics.
   * [Qualified Notification Model with Subscribing](02_mvc_variations/50_qualified_notification_model_with_subscribing): View subscribes to specific events and gets notified only when they occur.
   * [Passive Model](02_mvc_variations/07_passive_model.md): A Model without notification features.
   * [Lazy Model](02_mvc_variations/08_lazy_model.md): A Model delivering its notifications only on request.
   * [Accumulator](02_mvc_variations/35_accumulator.md): Listens to submodels and squashes multiple notifications into a single one.
   * [Delayed Model](02_mvc_variations/40_delayed_model.md): Neutralizes fast notifications through a timeout.
   * [Pre/Post notification](02_mvc_variations/47_pre_post_notification.md): Deliver notifications before or after the change.
   * [Vetoers](02_mvc_variations/48_vetoers.md): Inquire listeners to approve or deny a change to occur.
   * [Notification looping prevention](02_mvc_variations/28_notification_looping_prevention.md): Prevent recursive notification events to propagate.
   * [Signals](02_mvc_variations/49_signals.md): Isolate notification into a separate object.
