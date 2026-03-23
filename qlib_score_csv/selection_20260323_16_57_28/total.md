# params 
 {'predict_dates': [{'start': '2026-03-23', 'end': '2026-03-23'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260323_16 834882140462858534 (Recorders: 3/5)

	Recorder: 09cb3dbe2f17440f841a468fa6006c3b

		Model: {'id': '09cb3dbe2f17440f841a468fa6006c3b', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.055, 'Rank IC': 0.023, 'Rank ICIR': 0.152}, 'data_train_vec': ['2021-03-23', '2024-12-22'], 'train_time_vec': ['2026-03-23', '2026-03-23'], 'rank_icir': '0.152', 'weight': '0.036'}

	Recorder: b90f04cbace44a9da28c467f5cbeb633

		Model: {'id': 'b90f04cbace44a9da28c467f5cbeb633', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.165, 'Rank IC': 0.058, 'Rank ICIR': 0.37}, 'data_train_vec': ['2024-03-23', '2025-09-22'], 'train_time_vec': ['2026-03-23', '2026-03-23'], 'rank_icir': '0.370', 'weight': '0.088'}

	Recorder: 854975648063451baaf942e3b37c7731

		Model: {'id': '854975648063451baaf942e3b37c7731', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.137, 'Rank IC': 0.038, 'Rank ICIR': 0.285}, 'data_train_vec': ['2025-03-23', '2025-12-22'], 'train_time_vec': ['2026-03-23', '2026-03-23'], 'rank_icir': '0.285', 'weight': '0.068'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260323_16 620112017666481403 (Recorders: 2/5)

	Recorder: e2146cc9e5c647348b9e21679a8d10d9

		Model: {'id': 'e2146cc9e5c647348b9e21679a8d10d9', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.067, 'Rank IC': 0.031, 'Rank ICIR': 0.192}, 'data_train_vec': ['2021-03-23', '2024-12-22'], 'train_time_vec': ['2026-03-23', '2026-03-23'], 'rank_icir': '0.192', 'weight': '0.046'}

	Recorder: c834656ae96d43d0b8521721b54e5dbb

		Model: {'id': 'c834656ae96d43d0b8521721b54e5dbb', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.268, 'Rank IC': 0.044, 'Rank ICIR': 0.383}, 'data_train_vec': ['2024-03-23', '2025-09-22'], 'train_time_vec': ['2026-03-23', '2026-03-23'], 'rank_icir': '0.383', 'weight': '0.091'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260323_13 961852090628022577 (Recorders: 2/5)

	Recorder: f394d94ebfe641ef818f89674104dc3e

		Model: {'id': 'f394d94ebfe641ef818f89674104dc3e', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.12, 'Rank IC': 0.036, 'Rank ICIR': 0.213}, 'data_train_vec': ['2021-03-23', '2024-12-22'], 'train_time_vec': ['2026-03-23', '2026-03-23'], 'rank_icir': '0.213', 'weight': '0.051'}

	Recorder: 66844cc940aa4296b4260f17e611eef3

		Model: {'id': '66844cc940aa4296b4260f17e611eef3', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.036, 'ICIR': 0.34, 'Rank IC': 0.045, 'Rank ICIR': 0.378}, 'data_train_vec': ['2024-03-23', '2025-09-22'], 'train_time_vec': ['2026-03-23', '2026-03-23'], 'rank_icir': '0.378', 'weight': '0.090'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260323_13 157536553655801142 (Recorders: 5/5)

	Recorder: defc1a21817642b7b9e3e8bdeeb43d58

		Model: {'id': 'defc1a21817642b7b9e3e8bdeeb43d58', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.16, 'Rank IC': 0.026, 'Rank ICIR': 0.231}, 'data_train_vec': ['2021-03-23', '2024-12-22'], 'train_time_vec': ['2026-03-23', '2026-03-23'], 'rank_icir': '0.231', 'weight': '0.055'}

	Recorder: d4560fa206474843b718656fd925cb34

		Model: {'id': 'd4560fa206474843b718656fd925cb34', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.061, 'Rank IC': 0.02, 'Rank ICIR': 0.174}, 'data_train_vec': ['2022-03-23', '2025-03-22'], 'train_time_vec': ['2026-03-23', '2026-03-23'], 'rank_icir': '0.174', 'weight': '0.042'}

	Recorder: 6fcc305fe21147c089fb6eb95c166506

		Model: {'id': '6fcc305fe21147c089fb6eb95c166506', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.122, 'Rank IC': 0.038, 'Rank ICIR': 0.344}, 'data_train_vec': ['2023-03-23', '2025-06-22'], 'train_time_vec': ['2026-03-23', '2026-03-23'], 'rank_icir': '0.344', 'weight': '0.082'}

	Recorder: 89965eb7adf745689b7b9561530e186f

		Model: {'id': '89965eb7adf745689b7b9561530e186f', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.126, 'Rank IC': 0.021, 'Rank ICIR': 0.18}, 'data_train_vec': ['2024-03-23', '2025-09-22'], 'train_time_vec': ['2026-03-23', '2026-03-23'], 'rank_icir': '0.180', 'weight': '0.043'}

	Recorder: 7517a07244cd417b89d96a9d09ebb95e

		Model: {'id': '7517a07244cd417b89d96a9d09ebb95e', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.162, 'Rank IC': 0.026, 'Rank ICIR': 0.269}, 'data_train_vec': ['2025-03-23', '2025-12-22'], 'train_time_vec': ['2026-03-23', '2026-03-23'], 'rank_icir': '0.269', 'weight': '0.064'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260323_13 152324068304929898 (Recorders: 3/5)

	Recorder: 46675fdac3a84707b21cec9a9803072c

		Model: {'id': '46675fdac3a84707b21cec9a9803072c', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.067, 'Rank IC': 0.033, 'Rank ICIR': 0.196}, 'data_train_vec': ['2021-03-23', '2024-12-22'], 'train_time_vec': ['2026-03-23', '2026-03-23'], 'rank_icir': '0.196', 'weight': '0.047'}

	Recorder: 6df320bb34f94be48bc718a22e5c8192

		Model: {'id': '6df320bb34f94be48bc718a22e5c8192', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.251, 'Rank IC': 0.048, 'Rank ICIR': 0.454}, 'data_train_vec': ['2024-03-23', '2025-09-22'], 'train_time_vec': ['2026-03-23', '2026-03-23'], 'rank_icir': '0.454', 'weight': '0.108'}

	Recorder: f953f98e44ae460c91ba7116a832a596

		Model: {'id': 'f953f98e44ae460c91ba7116a832a596', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.251, 'Rank IC': 0.022, 'Rank ICIR': 0.365}, 'data_train_vec': ['2025-03-23', '2025-12-22'], 'train_time_vec': ['2026-03-23', '2026-03-23'], 'rank_icir': '0.365', 'weight': '0.087'}
