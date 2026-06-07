# Troubleshooting

| Symptom                                            | What to check                                                                                                                                                                                  |
| -------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| My launch didn't go live at the scheduled time     | Confirm the launch shows as _Scheduled_ (not draft), check your store's time zone, and review the audit log for a failure entry. A failed payment on a paid plan can also pause scheduling.     |
| Prices didn't roll back after the sale             | Auto-rollback requires a Starter or Growth plan and an end time set on the launch. On the Free plan, prices won't revert automatically.                                                         |
| The crossed-out compare-at price isn't showing     | This is controlled by your theme. Check that your theme is set to display sale/compare-at prices on the relevant pages.                                                                         |
| A theme or page didn't publish                     | Theme & page publishing is a Growth feature. Confirm you're on Growth and that the target theme/page still exists and wasn't deleted before launch time.                                        |
| I'm not getting email notifications                | Notifications require the Growth plan. Verify your account email is correct and check spam/promotions folders.                                                                                  |
| Rollback restored an unexpected price              | The product was likely edited outside Launch Flow while the launch was live, which changed what the snapshot compared against. Make edits through Launch Flow during an active launch.          |

{% hint style="success" %}
**Still stuck?** Email [support@codecollective.io](mailto:support@codecollective.io) with your store URL and the name of the launch, and include any audit-log entry around the time of the issue — it helps us resolve things faster.
{% endhint %}
