# params 
 {'predict_dates': [{'start': '2026-04-09', 'end': '2026-04-09'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260409_16 418776265638125661 (Recorders: 1/5)

	Recorder: d7494b90451f4e43b947e4239b5aadfc

		Model: {'id': 'd7494b90451f4e43b947e4239b5aadfc', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.233, 'Rank IC': 0.045, 'Rank ICIR': 0.29}, 'data_train_vec': ['2023-04-09', '2025-07-08'], 'train_time_vec': ['2026-04-09', '2026-04-09'], 'rank_icir': '0.290', 'weight': '0.127'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260409_16 182633688725480797 (Recorders: 1/5)

	Recorder: 24c516ef41244fdfb9253cc6e01cb578

		Model: {'id': '24c516ef41244fdfb9253cc6e01cb578', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.251, 'Rank IC': 0.036, 'Rank ICIR': 0.313}, 'data_train_vec': ['2024-04-09', '2025-10-08'], 'train_time_vec': ['2026-04-09', '2026-04-09'], 'rank_icir': '0.313', 'weight': '0.137'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260409_14 805247256392647523 (Recorders: 3/5)

	Recorder: 0da33912a82748dda593f20e7fded72c

		Model: {'id': '0da33912a82748dda593f20e7fded72c', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.073, 'Rank IC': 0.027, 'Rank ICIR': 0.152}, 'data_train_vec': ['2021-04-09', '2025-01-08'], 'train_time_vec': ['2026-04-09', '2026-04-09'], 'rank_icir': '0.152', 'weight': '0.066'}

	Recorder: 9d8fc2ab51c7407eb6e831c46ff6c972

		Model: {'id': '9d8fc2ab51c7407eb6e831c46ff6c972', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.122, 'Rank IC': 0.053, 'Rank ICIR': 0.312}, 'data_train_vec': ['2023-04-09', '2025-07-08'], 'train_time_vec': ['2026-04-09', '2026-04-09'], 'rank_icir': '0.312', 'weight': '0.136'}

	Recorder: 02c6ee28b5af4f3c907ecda106309162

		Model: {'id': '02c6ee28b5af4f3c907ecda106309162', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.261, 'Rank IC': 0.031, 'Rank ICIR': 0.311}, 'data_train_vec': ['2024-04-09', '2025-10-08'], 'train_time_vec': ['2026-04-09', '2026-04-09'], 'rank_icir': '0.311', 'weight': '0.136'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260409_14 326049222987499158 (Recorders: 5/5)

	Recorder: 2476e2a2052044ee8a00a0e800894827

		Model: {'id': '2476e2a2052044ee8a00a0e800894827', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.088, 'Rank IC': 0.019, 'Rank ICIR': 0.156}, 'data_train_vec': ['2021-04-09', '2025-01-08'], 'train_time_vec': ['2026-04-09', '2026-04-09'], 'rank_icir': '0.156', 'weight': '0.068'}

	Recorder: 144584a3f3b042ce91cbb24105800a1f

		Model: {'id': '144584a3f3b042ce91cbb24105800a1f', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.012, 'Rank IC': 0.017, 'Rank ICIR': 0.147}, 'data_train_vec': ['2022-04-09', '2025-04-08'], 'train_time_vec': ['2026-04-09', '2026-04-09'], 'rank_icir': '0.147', 'weight': '0.064'}

	Recorder: e9499920aae84e26858459915fdf93ad

		Model: {'id': 'e9499920aae84e26858459915fdf93ad', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.149, 'Rank IC': 0.042, 'Rank ICIR': 0.36}, 'data_train_vec': ['2023-04-09', '2025-07-08'], 'train_time_vec': ['2026-04-09', '2026-04-09'], 'rank_icir': '0.360', 'weight': '0.157'}

	Recorder: e59504956ff44741b6029bdc6428efa2

		Model: {'id': 'e59504956ff44741b6029bdc6428efa2', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.052, 'Rank IC': 0.011, 'Rank ICIR': 0.087}, 'data_train_vec': ['2024-04-09', '2025-10-08'], 'train_time_vec': ['2026-04-09', '2026-04-09'], 'rank_icir': '0.087', 'weight': '0.038'}

	Recorder: 414110329608437d9ff3088de5dfda55

		Model: {'id': '414110329608437d9ff3088de5dfda55', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.078, 'Rank IC': 0.006, 'Rank ICIR': 0.046}, 'data_train_vec': ['2025-04-09', '2026-01-08'], 'train_time_vec': ['2026-04-09', '2026-04-09'], 'rank_icir': '0.046', 'weight': '0.020'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260409_14 456546741478503984 (Recorders: 1/5)

	Recorder: c8a87aeb3e6142fabf862ea2a76fe101

		Model: {'id': 'c8a87aeb3e6142fabf862ea2a76fe101', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.032, 'Rank IC': 0.021, 'Rank ICIR': 0.112}, 'data_train_vec': ['2021-04-09', '2025-01-08'], 'train_time_vec': ['2026-04-09', '2026-04-09'], 'rank_icir': '0.112', 'weight': '0.049'}
