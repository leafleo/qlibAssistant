# params 
 {'predict_dates': [{'start': '2026-05-07', 'end': '2026-05-07'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260507_17 209939838775169045 (Recorders: 2/5)

	Recorder: f6b7d8f9044f4077ac972fa60ea3284c

		Model: {'id': 'f6b7d8f9044f4077ac972fa60ea3284c', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.055, 'Rank IC': 0.024, 'Rank ICIR': 0.179}, 'data_train_vec': ['2024-05-07', '2025-11-06'], 'train_time_vec': ['2026-05-07', '2026-05-07'], 'rank_icir': '0.179', 'weight': '0.105'}

	Recorder: 945fa371dfeb4d74a5b08342368758cb

		Model: {'id': '945fa371dfeb4d74a5b08342368758cb', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.049, 'ICIR': 0.438, 'Rank IC': 0.023, 'Rank ICIR': 0.183}, 'data_train_vec': ['2025-05-07', '2026-02-06'], 'train_time_vec': ['2026-05-07', '2026-05-07'], 'rank_icir': '0.183', 'weight': '0.107'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260507_17 994220848032139218 (Recorders: 2/5)

	Recorder: 569455ed41cc47bf894cf75807579e67

		Model: {'id': '569455ed41cc47bf894cf75807579e67', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.239, 'Rank IC': 0.024, 'Rank ICIR': 0.199}, 'data_train_vec': ['2024-05-07', '2025-11-06'], 'train_time_vec': ['2026-05-07', '2026-05-07'], 'rank_icir': '0.199', 'weight': '0.116'}

	Recorder: 28cea1f096724356a8689c0875518cf5

		Model: {'id': '28cea1f096724356a8689c0875518cf5', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.084, 'ICIR': 0.662, 'Rank IC': 0.035, 'Rank ICIR': 0.335}, 'data_train_vec': ['2025-05-07', '2026-02-06'], 'train_time_vec': ['2026-05-07', '2026-05-07'], 'rank_icir': '0.335', 'weight': '0.196'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260507_14 188551429209548580 (Recorders: 3/5)

	Recorder: 67be683783f84f90bc8e695074c83009

		Model: {'id': '67be683783f84f90bc8e695074c83009', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.008, 'Rank IC': 0.03, 'Rank ICIR': 0.178}, 'data_train_vec': ['2023-05-07', '2025-08-06'], 'train_time_vec': ['2026-05-07', '2026-05-07'], 'rank_icir': '0.178', 'weight': '0.104'}

	Recorder: ac3754af2c9e455bad25bd199e498b76

		Model: {'id': 'ac3754af2c9e455bad25bd199e498b76', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.075, 'Rank IC': 0.01, 'Rank ICIR': 0.083}, 'data_train_vec': ['2024-05-07', '2025-11-06'], 'train_time_vec': ['2026-05-07', '2026-05-07'], 'rank_icir': '0.083', 'weight': '0.048'}

	Recorder: df1cc1eae9c8496286a95807b6dd1aaa

		Model: {'id': 'df1cc1eae9c8496286a95807b6dd1aaa', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.045, 'ICIR': 0.385, 'Rank IC': 0.015, 'Rank ICIR': 0.118}, 'data_train_vec': ['2025-05-07', '2026-02-06'], 'train_time_vec': ['2026-05-07', '2026-05-07'], 'rank_icir': '0.118', 'weight': '0.069'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260507_14 964134965815452296 (Recorders: 2/5)

	Recorder: 41e502ebf6d94b37b0dbca1af7c8adc1

		Model: {'id': '41e502ebf6d94b37b0dbca1af7c8adc1', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.052, 'Rank IC': 0.017, 'Rank ICIR': 0.156}, 'data_train_vec': ['2024-05-07', '2025-11-06'], 'train_time_vec': ['2026-05-07', '2026-05-07'], 'rank_icir': '0.156', 'weight': '0.091'}

	Recorder: 66a1154d7f58477a8b1f71d0fa019a64

		Model: {'id': '66a1154d7f58477a8b1f71d0fa019a64', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.054, 'ICIR': 0.563, 'Rank IC': 0.023, 'Rank ICIR': 0.2}, 'data_train_vec': ['2025-05-07', '2026-02-06'], 'train_time_vec': ['2026-05-07', '2026-05-07'], 'rank_icir': '0.200', 'weight': '0.117'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260507_14 753670348489119708 (Recorders: 1/5)

	Recorder: c6046f6849424a4db73a090a862cbf8c

		Model: {'id': 'c6046f6849424a4db73a090a862cbf8c', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.037, 'ICIR': 0.401, 'Rank IC': 0.008, 'Rank ICIR': 0.081}, 'data_train_vec': ['2025-05-07', '2026-02-06'], 'train_time_vec': ['2026-05-07', '2026-05-07'], 'rank_icir': '0.081', 'weight': '0.047'}
