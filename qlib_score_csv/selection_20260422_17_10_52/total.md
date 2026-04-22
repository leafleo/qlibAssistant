# params 
 {'predict_dates': [{'start': '2026-04-22', 'end': '2026-04-22'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260422_16 171314875128338596 (Recorders: 2/5)

	Recorder: 51795b23fc4e4147825361d07fd33bbd

		Model: {'id': '51795b23fc4e4147825361d07fd33bbd', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.248, 'Rank IC': 0.047, 'Rank ICIR': 0.277}, 'data_train_vec': ['2023-04-22', '2025-07-21'], 'train_time_vec': ['2026-04-22', '2026-04-22'], 'rank_icir': '0.277', 'weight': '0.149'}

	Recorder: 7d424ef09f2b455c9daefd11804774c4

		Model: {'id': '7d424ef09f2b455c9daefd11804774c4', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.074, 'ICIR': 0.578, 'Rank IC': 0.031, 'Rank ICIR': 0.211}, 'data_train_vec': ['2025-04-22', '2026-01-21'], 'train_time_vec': ['2026-04-22', '2026-04-22'], 'rank_icir': '0.211', 'weight': '0.114'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260422_16 368745905426713379 (Recorders: 2/5)

	Recorder: 0f7f8da047e945aa9be33040f3b4a756

		Model: {'id': '0f7f8da047e945aa9be33040f3b4a756', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.226, 'Rank IC': 0.037, 'Rank ICIR': 0.29}, 'data_train_vec': ['2024-04-22', '2025-10-21'], 'train_time_vec': ['2026-04-22', '2026-04-22'], 'rank_icir': '0.290', 'weight': '0.157'}

	Recorder: 1451490e76eb4f7fa3ccc757b86ecf71

		Model: {'id': '1451490e76eb4f7fa3ccc757b86ecf71', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.049, 'ICIR': 0.36, 'Rank IC': 0.024, 'Rank ICIR': 0.165}, 'data_train_vec': ['2025-04-22', '2026-01-21'], 'train_time_vec': ['2026-04-22', '2026-04-22'], 'rank_icir': '0.165', 'weight': '0.089'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260422_14 926602563678628466 (Recorders: 3/5)

	Recorder: f51749e9eed54e6bb3a3921fd1d211e8

		Model: {'id': 'f51749e9eed54e6bb3a3921fd1d211e8', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.025, 'Rank IC': 0.042, 'Rank ICIR': 0.229}, 'data_train_vec': ['2023-04-22', '2025-07-21'], 'train_time_vec': ['2026-04-22', '2026-04-22'], 'rank_icir': '0.229', 'weight': '0.124'}

	Recorder: c453aa52d86444e1ba9127732e20866b

		Model: {'id': 'c453aa52d86444e1ba9127732e20866b', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.138, 'Rank IC': 0.022, 'Rank ICIR': 0.167}, 'data_train_vec': ['2024-04-22', '2025-10-21'], 'train_time_vec': ['2026-04-22', '2026-04-22'], 'rank_icir': '0.167', 'weight': '0.090'}

	Recorder: 011a86cbf8214ea1940eab64fcb03394

		Model: {'id': '011a86cbf8214ea1940eab64fcb03394', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.041, 'ICIR': 0.244, 'Rank IC': 0.015, 'Rank ICIR': 0.077}, 'data_train_vec': ['2025-04-22', '2026-01-21'], 'train_time_vec': ['2026-04-22', '2026-04-22'], 'rank_icir': '0.077', 'weight': '0.042'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260422_14 954253855921080438 (Recorders: 1/5)

	Recorder: fc7a4d36416d4305b197612a353add74

		Model: {'id': 'fc7a4d36416d4305b197612a353add74', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.051, 'ICIR': 0.406, 'Rank IC': 0.033, 'Rank ICIR': 0.245}, 'data_train_vec': ['2025-04-22', '2026-01-21'], 'train_time_vec': ['2026-04-22', '2026-04-22'], 'rank_icir': '0.245', 'weight': '0.132'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260422_14 587305409419997360 (Recorders: 1/5)

	Recorder: 5b4e0abd0ec0449ca4e16e782d9eb1e0

		Model: {'id': '5b4e0abd0ec0449ca4e16e782d9eb1e0', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.052, 'ICIR': 0.322, 'Rank IC': 0.033, 'Rank ICIR': 0.192}, 'data_train_vec': ['2025-04-22', '2026-01-21'], 'train_time_vec': ['2026-04-22', '2026-04-22'], 'rank_icir': '0.192', 'weight': '0.104'}
