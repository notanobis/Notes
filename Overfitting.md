Can predict the data it has been trained on but not ones it hasn't seen before.

For that we set aside some data for validation [[valid_pct]]

We can also set aside more data for "testing" : the [[metrics]] is not calculated after each [[epoch]] but only when the training is finished