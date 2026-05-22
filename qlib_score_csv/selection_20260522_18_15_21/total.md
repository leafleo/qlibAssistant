# params 
 {'predict_dates': [{'start': '2026-05-22', 'end': '2026-05-22'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260522_17 956644117428710025 (Recorders: 3/5)

	Recorder: 68e959cd176c49d38ccac03721b0e024

		Model: {'id': '68e959cd176c49d38ccac03721b0e024', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.03, 'Rank IC': 0.027, 'Rank ICIR': 0.189}, 'data_train_vec': ['2022-05-22', '2025-05-21'], 'train_time_vec': ['2026-05-22', '2026-05-22'], 'rank_icir': '0.189', 'weight': '0.055'}

	Recorder: 7a1623c924d2420fa83eefd3d6365312

		Model: {'id': '7a1623c924d2420fa83eefd3d6365312', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.119, 'Rank IC': 0.037, 'Rank ICIR': 0.254}, 'data_train_vec': ['2023-05-22', '2025-08-21'], 'train_time_vec': ['2026-05-22', '2026-05-22'], 'rank_icir': '0.254', 'weight': '0.073'}

	Recorder: c1f1d09b37b34aa8b491adb8ff92dc10

		Model: {'id': 'c1f1d09b37b34aa8b491adb8ff92dc10', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.069, 'ICIR': 0.48, 'Rank IC': 0.03, 'Rank ICIR': 0.182}, 'data_train_vec': ['2025-05-22', '2026-02-21'], 'train_time_vec': ['2026-05-22', '2026-05-22'], 'rank_icir': '0.182', 'weight': '0.053'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260522_17 917145281216907723 (Recorders: 3/5)

	Recorder: 8060af98ef2d4e358ab46918f9919f25

		Model: {'id': '8060af98ef2d4e358ab46918f9919f25', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.182, 'Rank IC': 0.027, 'Rank ICIR': 0.219}, 'data_train_vec': ['2023-05-22', '2025-08-21'], 'train_time_vec': ['2026-05-22', '2026-05-22'], 'rank_icir': '0.219', 'weight': '0.063'}

	Recorder: 35b46982aa9e45ec9077791c70366e7d

		Model: {'id': '35b46982aa9e45ec9077791c70366e7d', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.228, 'Rank IC': 0.007, 'Rank ICIR': 0.07}, 'data_train_vec': ['2024-05-22', '2025-11-21'], 'train_time_vec': ['2026-05-22', '2026-05-22'], 'rank_icir': '0.070', 'weight': '0.020'}

	Recorder: 387891996a8c43078d2a88766aff69f0

		Model: {'id': '387891996a8c43078d2a88766aff69f0', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.096, 'ICIR': 0.536, 'Rank IC': 0.047, 'Rank ICIR': 0.252}, 'data_train_vec': ['2025-05-22', '2026-02-21'], 'train_time_vec': ['2026-05-22', '2026-05-22'], 'rank_icir': '0.252', 'weight': '0.073'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260522_15 618737625771454980 (Recorders: 4/5)

	Recorder: 956d2e2a36c0445484dbcdfe8804d2e1

		Model: {'id': '956d2e2a36c0445484dbcdfe8804d2e1', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.036, 'Rank IC': 0.029, 'Rank ICIR': 0.195}, 'data_train_vec': ['2021-05-22', '2025-02-21'], 'train_time_vec': ['2026-05-22', '2026-05-22'], 'rank_icir': '0.195', 'weight': '0.056'}

	Recorder: 050f2b737f3747948645ca8b72a75d49

		Model: {'id': '050f2b737f3747948645ca8b72a75d49', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.029, 'Rank IC': 0.035, 'Rank ICIR': 0.192}, 'data_train_vec': ['2022-05-22', '2025-05-21'], 'train_time_vec': ['2026-05-22', '2026-05-22'], 'rank_icir': '0.192', 'weight': '0.055'}

	Recorder: 1cde102864bf4418bc2cb68bc6e0ddea

		Model: {'id': '1cde102864bf4418bc2cb68bc6e0ddea', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.168, 'Rank IC': 0.036, 'Rank ICIR': 0.255}, 'data_train_vec': ['2023-05-22', '2025-08-21'], 'train_time_vec': ['2026-05-22', '2026-05-22'], 'rank_icir': '0.255', 'weight': '0.074'}

	Recorder: 8fcf3e53d7674b1da4056ed1cb265a58

		Model: {'id': '8fcf3e53d7674b1da4056ed1cb265a58', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.083, 'ICIR': 0.489, 'Rank IC': 0.049, 'Rank ICIR': 0.266}, 'data_train_vec': ['2025-05-22', '2026-02-21'], 'train_time_vec': ['2026-05-22', '2026-05-22'], 'rank_icir': '0.266', 'weight': '0.077'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260522_15 857381995996146690 (Recorders: 4/5)

	Recorder: dd99ed24efcf479b9bf641f7f5656a09

		Model: {'id': 'dd99ed24efcf479b9bf641f7f5656a09', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.065, 'Rank IC': 0.031, 'Rank ICIR': 0.28}, 'data_train_vec': ['2021-05-22', '2025-02-21'], 'train_time_vec': ['2026-05-22', '2026-05-22'], 'rank_icir': '0.280', 'weight': '0.081'}

	Recorder: 7ab9e9bc216149d18a0836b4f209a98a

		Model: {'id': '7ab9e9bc216149d18a0836b4f209a98a', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.108, 'Rank IC': 0.036, 'Rank ICIR': 0.337}, 'data_train_vec': ['2023-05-22', '2025-08-21'], 'train_time_vec': ['2026-05-22', '2026-05-22'], 'rank_icir': '0.337', 'weight': '0.097'}

	Recorder: 6410fef4dee24ecc97f44f0971ae487e

		Model: {'id': '6410fef4dee24ecc97f44f0971ae487e', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.008, 'Rank IC': 0.012, 'Rank ICIR': 0.091}, 'data_train_vec': ['2024-05-22', '2025-11-21'], 'train_time_vec': ['2026-05-22', '2026-05-22'], 'rank_icir': '0.091', 'weight': '0.026'}

	Recorder: 0f7a9198f2e1489f8c87b47e96b6f54a

		Model: {'id': '0f7a9198f2e1489f8c87b47e96b6f54a', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.081, 'ICIR': 0.486, 'Rank IC': 0.059, 'Rank ICIR': 0.311}, 'data_train_vec': ['2025-05-22', '2026-02-21'], 'train_time_vec': ['2026-05-22', '2026-05-22'], 'rank_icir': '0.311', 'weight': '0.090'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260522_15 369356410498349306 (Recorders: 2/5)

	Recorder: 2c534a8126ff48fdb4151d852d0024df

		Model: {'id': '2c534a8126ff48fdb4151d852d0024df', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.075, 'Rank IC': 0.032, 'Rank ICIR': 0.233}, 'data_train_vec': ['2023-05-22', '2025-08-21'], 'train_time_vec': ['2026-05-22', '2026-05-22'], 'rank_icir': '0.233', 'weight': '0.067'}

	Recorder: baf9d70ccd59447788253a981465927a

		Model: {'id': 'baf9d70ccd59447788253a981465927a', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.053, 'ICIR': 0.349, 'Rank IC': 0.021, 'Rank ICIR': 0.135}, 'data_train_vec': ['2025-05-22', '2026-02-21'], 'train_time_vec': ['2026-05-22', '2026-05-22'], 'rank_icir': '0.135', 'weight': '0.039'}
