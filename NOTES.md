[2022-03-07 14:59:45] michael | subnet-cli (main) % subnet-cli create subnet
2022-03-07T15:03:55.919+0800	info	client/client.go:85	fetching X-Chain id
2022-03-07T15:03:56.077+0800	info	client/client.go:91	fetched X-Chain id	{"id": "2JVSBoinj9C2J33VntvzYtVJNZdN2NKiwwKjcumHUWEb5DbBrm"}
2022-03-07T15:03:56.077+0800	info	client/client.go:100	fetching AVAX asset id	{"uri": "https://api.avax-test.network"}
2022-03-07T15:03:56.099+0800	info	client/client.go:109	fetched AVAX asset id	{"id": "U8iRqJoiJm8xZHAacmvYyZVwqQx6uDNtQeP3CQ6fcgQk3JqnK"}
2022-03-07T15:03:56.099+0800	info	client/client.go:111	fetching network information
2022-03-07T15:03:56.115+0800	info	client/client.go:120	fetched network information	{"networkId": 5, "networkName": "fuji"}
2022-03-07T15:03:56.430+0800	info	client/p.go:126	creating subnet	{"dryMode": true, "assetId": "U8iRqJoiJm8xZHAacmvYyZVwqQx6uDNtQeP3CQ6fcgQk3JqnK", "createSubnetTxFee": 100000000}

Ready to create subnet resources, should we continue?
*--------------------*---------------------------------------------------*
| P-CHAIN ADDRESS    | P-fuji1kkpwt8sysfa4n0y9vaxux6t8g63uhwa5u86hrc     |
*--------------------*---------------------------------------------------*
| P-CHAIN BALANCE    | 1.9980000 $AVAX                                   |
*--------------------*---------------------------------------------------*
| TX FEE             | 0.100 $AVAX                                       |
*--------------------*---------------------------------------------------*
| URI                | https://api.avax-test.network                     |
*--------------------*---------------------------------------------------*
| NETWORK NAME       | fuji                                              |
*--------------------*---------------------------------------------------*
| EXPECTED SUBNET ID | 2BZePph7VQp5tjpkTnys1YpBFVaaVtEBkx23BkMh7mUksJmrJ |
*--------------------*---------------------------------------------------*
✔ Yes, let's create! I agree to pay the fee!



2022-03-07T15:04:08.304+0800	info	client/p.go:126	creating subnet	{"dryMode": false, "assetId": "U8iRqJoiJm8xZHAacmvYyZVwqQx6uDNtQeP3CQ6fcgQk3JqnK", "createSubnetTxFee": 100000000}
2022-03-07T15:04:08.733+0800	info	platformvm/checker.go:73	polling subnet	{"subnetId": "2BZePph7VQp5tjpkTnys1YpBFVaaVtEBkx23BkMh7mUksJmrJ"}
2022-03-07T15:04:08.734+0800	info	platformvm/checker.go:47	polling P-Chain tx	{"txId": "2BZePph7VQp5tjpkTnys1YpBFVaaVtEBkx23BkMh7mUksJmrJ", "expectedStatus": "Committed"}
2022-03-07T15:04:08.734+0800	info	poll/poll.go:42	start polling	{"internal": "1s"}
2022-03-07T15:04:10.179+0800	info	poll/poll.go:66	poll confirmed	{"took": "1.444882917s"}
2022-03-07T15:04:10.179+0800	info	platformvm/checker.go:87	finding subnets	{"subnetId": "2BZePph7VQp5tjpkTnys1YpBFVaaVtEBkx23BkMh7mUksJmrJ"}
2022-03-07T15:04:10.179+0800	info	poll/poll.go:42	start polling	{"internal": "1s"}
2022-03-07T15:04:10.406+0800	info	poll/poll.go:66	poll confirmed	{"took": "226.664083ms"}
created subnet "2BZePph7VQp5tjpkTnys1YpBFVaaVtEBkx23BkMh7mUksJmrJ" (took 1.671547s)
(subnet must be whitelisted beforehand via --whitelisted-subnets flag!)

*-------------------*---------------------------------------------------*
| P-CHAIN ADDRESS   | P-fuji1kkpwt8sysfa4n0y9vaxux6t8g63uhwa5u86hrc     |
*-------------------*---------------------------------------------------*
| P-CHAIN BALANCE   | 1.8980000 $AVAX                                   |
*-------------------*---------------------------------------------------*
| URI               | https://api.avax-test.network                     |
*-------------------*---------------------------------------------------*
| NETWORK NAME      | fuji                                              |
*-------------------*---------------------------------------------------*
| CREATED SUBNET ID | 2BZePph7VQp5tjpkTnys1YpBFVaaVtEBkx23BkMh7mUksJmrJ |
*-------------------*---------------------------------------------------*
