# Data

The three source files are not stored in this repository:

| File | Contents |
|---|---|
| `da_fitly_account_info.csv` | One row per customer: plan, price paid, state and whether the customer cancelled |
| `da_fitly_customer_support.csv` | One row per support ticket: time, channel, topic and hours to resolve |
| `da_fitly_user_activity.csv` | One row per in-app event: time and event type |

The notebook looks for the files in this folder first. If they are not here, it downloads them from the original source link, so it also runs without any setup.
