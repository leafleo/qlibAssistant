# params 
 {'predict_dates': [{'start': '2026-05-08', 'end': '2026-05-08'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260508_16 549578453148054659 (Recorders: 2/5)

	Recorder: 71410224b34c48fa85f4a53320e0032b

		Model: {'id': '71410224b34c48fa85f4a53320e0032b', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.131, 'Rank IC': 0.039, 'Rank ICIR': 0.239}, 'data_train_vec': ['2023-05-08', '2025-08-07'], 'train_time_vec': ['2026-05-08', '2026-05-08'], 'rank_icir': '0.239', 'weight': '0.091'}

	Recorder: ed7f4732934945b98090da796cbd8df6

		Model: {'id': 'ed7f4732934945b98090da796cbd8df6', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.235, 'Rank IC': 0.02, 'Rank ICIR': 0.146}, 'data_train_vec': ['2025-05-08', '2026-02-07'], 'train_time_vec': ['2026-05-08', '2026-05-08'], 'rank_icir': '0.146', 'weight': '0.056'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260508_16 502438231325112664 (Recorders: 2/5)

	Recorder: 67aaf4ee861e4cff962e103c58f38cae

		Model: {'id': '67aaf4ee861e4cff962e103c58f38cae', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.159, 'Rank IC': 0.019, 'Rank ICIR': 0.157}, 'data_train_vec': ['2024-05-08', '2025-11-07'], 'train_time_vec': ['2026-05-08', '2026-05-08'], 'rank_icir': '0.157', 'weight': '0.060'}

	Recorder: ca127f94176c4c8ba04c416efbdf29bc

		Model: {'id': 'ca127f94176c4c8ba04c416efbdf29bc', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.075, 'ICIR': 0.508, 'Rank IC': 0.02, 'Rank ICIR': 0.146}, 'data_train_vec': ['2025-05-08', '2026-02-07'], 'train_time_vec': ['2026-05-08', '2026-05-08'], 'rank_icir': '0.146', 'weight': '0.056'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260508_14 388558549680986404 (Recorders: 4/5)

	Recorder: c36e8b85095e4d838c182bcee1908cc2

		Model: {'id': 'c36e8b85095e4d838c182bcee1908cc2', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.018, 'Rank IC': 0.031, 'Rank ICIR': 0.173}, 'data_train_vec': ['2022-05-08', '2025-05-07'], 'train_time_vec': ['2026-05-08', '2026-05-08'], 'rank_icir': '0.173', 'weight': '0.066'}

	Recorder: 6021f7ea601749e5b152eeac1097b282

		Model: {'id': '6021f7ea601749e5b152eeac1097b282', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.025, 'Rank IC': 0.03, 'Rank ICIR': 0.169}, 'data_train_vec': ['2023-05-08', '2025-08-07'], 'train_time_vec': ['2026-05-08', '2026-05-08'], 'rank_icir': '0.169', 'weight': '0.065'}

	Recorder: a1b6879c564241fca431ae8b3a2cc609

		Model: {'id': 'a1b6879c564241fca431ae8b3a2cc609', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.028, 'Rank IC': 0.012, 'Rank ICIR': 0.095}, 'data_train_vec': ['2024-05-08', '2025-11-07'], 'train_time_vec': ['2026-05-08', '2026-05-08'], 'rank_icir': '0.095', 'weight': '0.036'}

	Recorder: 246173a6588340aca285c143d7f0b30d

		Model: {'id': '246173a6588340aca285c143d7f0b30d', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.052, 'ICIR': 0.425, 'Rank IC': 0.016, 'Rank ICIR': 0.131}, 'data_train_vec': ['2025-05-08', '2026-02-07'], 'train_time_vec': ['2026-05-08', '2026-05-08'], 'rank_icir': '0.131', 'weight': '0.050'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260508_14 269978363962158330 (Recorders: 4/5)

	Recorder: f02e21c28550400aafd99e409f0f60cb

		Model: {'id': 'f02e21c28550400aafd99e409f0f60cb', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.03, 'Rank IC': 0.019, 'Rank ICIR': 0.17}, 'data_train_vec': ['2021-05-08', '2025-02-07'], 'train_time_vec': ['2026-05-08', '2026-05-08'], 'rank_icir': '0.170', 'weight': '0.065'}

	Recorder: fb704b7328954c45bbf393546dcceaee

		Model: {'id': 'fb704b7328954c45bbf393546dcceaee', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.012, 'Rank IC': 0.026, 'Rank ICIR': 0.209}, 'data_train_vec': ['2022-05-08', '2025-05-07'], 'train_time_vec': ['2026-05-08', '2026-05-08'], 'rank_icir': '0.209', 'weight': '0.080'}

	Recorder: 18fa6c379d4245b1a4bd4fcd7bf74192

		Model: {'id': '18fa6c379d4245b1a4bd4fcd7bf74192', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.058, 'Rank IC': 0.02, 'Rank ICIR': 0.181}, 'data_train_vec': ['2024-05-08', '2025-11-07'], 'train_time_vec': ['2026-05-08', '2026-05-08'], 'rank_icir': '0.181', 'weight': '0.069'}

	Recorder: c8099457a11047808090688fa77f2f20

		Model: {'id': 'c8099457a11047808090688fa77f2f20', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.054, 'ICIR': 0.513, 'Rank IC': 0.023, 'Rank ICIR': 0.19}, 'data_train_vec': ['2025-05-08', '2026-02-07'], 'train_time_vec': ['2026-05-08', '2026-05-08'], 'rank_icir': '0.190', 'weight': '0.073'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260508_14 267200800389035865 (Recorders: 3/5)

	Recorder: 938da2c273224dcdac0b0600a704ba61

		Model: {'id': '938da2c273224dcdac0b0600a704ba61', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.015, 'Rank IC': 0.022, 'Rank ICIR': 0.131}, 'data_train_vec': ['2023-05-08', '2025-08-07'], 'train_time_vec': ['2026-05-08', '2026-05-08'], 'rank_icir': '0.131', 'weight': '0.050'}

	Recorder: fcd7ecc6780e4982a8a0d56eb176fa3d

		Model: {'id': 'fcd7ecc6780e4982a8a0d56eb176fa3d', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.027, 'Rank IC': 0.012, 'Rank ICIR': 0.099}, 'data_train_vec': ['2024-05-08', '2025-11-07'], 'train_time_vec': ['2026-05-08', '2026-05-08'], 'rank_icir': '0.099', 'weight': '0.038'}

	Recorder: c17da3e0d27c447085f9585e44ded444

		Model: {'id': 'c17da3e0d27c447085f9585e44ded444', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.072, 'ICIR': 0.622, 'Rank IC': 0.042, 'Rank ICIR': 0.382}, 'data_train_vec': ['2025-05-08', '2026-02-07'], 'train_time_vec': ['2026-05-08', '2026-05-08'], 'rank_icir': '0.382', 'weight': '0.146'}
