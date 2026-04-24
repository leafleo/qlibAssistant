# params 
 {'predict_dates': [{'start': '2026-04-24', 'end': '2026-04-24'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260424_16 856988629824319236 (Recorders: 3/5)

	Recorder: f85600f9b6874598a612cc7822aa03e3

		Model: {'id': 'f85600f9b6874598a612cc7822aa03e3', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.204, 'Rank IC': 0.054, 'Rank ICIR': 0.343}, 'data_train_vec': ['2023-04-24', '2025-07-23'], 'train_time_vec': ['2026-04-24', '2026-04-24'], 'rank_icir': '0.343', 'weight': '0.156'}

	Recorder: 5f6b62c019de4252af18cd61e39b7827

		Model: {'id': '5f6b62c019de4252af18cd61e39b7827', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.157, 'Rank IC': 0.018, 'Rank ICIR': 0.144}, 'data_train_vec': ['2024-04-24', '2025-10-23'], 'train_time_vec': ['2026-04-24', '2026-04-24'], 'rank_icir': '0.144', 'weight': '0.066'}

	Recorder: 51861937767d4f16a7a7a2d0d830eccf

		Model: {'id': '51861937767d4f16a7a7a2d0d830eccf', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.172, 'Rank IC': 0.013, 'Rank ICIR': 0.073}, 'data_train_vec': ['2025-04-24', '2026-01-23'], 'train_time_vec': ['2026-04-24', '2026-04-24'], 'rank_icir': '0.073', 'weight': '0.033'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260424_16 220789288282066750 (Recorders: 2/5)

	Recorder: 96dc4e1ec6ec46f6b0732ec3f47042b8

		Model: {'id': '96dc4e1ec6ec46f6b0732ec3f47042b8', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.26, 'Rank IC': 0.032, 'Rank ICIR': 0.277}, 'data_train_vec': ['2024-04-24', '2025-10-23'], 'train_time_vec': ['2026-04-24', '2026-04-24'], 'rank_icir': '0.277', 'weight': '0.126'}

	Recorder: 63209f6832c04607a92ecc8b9525a6a4

		Model: {'id': '63209f6832c04607a92ecc8b9525a6a4', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.052, 'ICIR': 0.423, 'Rank IC': 0.012, 'Rank ICIR': 0.094}, 'data_train_vec': ['2025-04-24', '2026-01-23'], 'train_time_vec': ['2026-04-24', '2026-04-24'], 'rank_icir': '0.094', 'weight': '0.043'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260424_14 350803254468212924 (Recorders: 3/5)

	Recorder: 0ffa49ea31b64b75a519f3229c5e6c48

		Model: {'id': '0ffa49ea31b64b75a519f3229c5e6c48', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.055, 'Rank IC': 0.045, 'Rank ICIR': 0.255}, 'data_train_vec': ['2023-04-24', '2025-07-23'], 'train_time_vec': ['2026-04-24', '2026-04-24'], 'rank_icir': '0.255', 'weight': '0.116'}

	Recorder: 29c997d7b9614920830907f4f364af0e

		Model: {'id': '29c997d7b9614920830907f4f364af0e', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.172, 'Rank IC': 0.021, 'Rank ICIR': 0.18}, 'data_train_vec': ['2024-04-24', '2025-10-23'], 'train_time_vec': ['2026-04-24', '2026-04-24'], 'rank_icir': '0.180', 'weight': '0.082'}

	Recorder: 2cf4f3bdb37e4531bffc01b5dda502de

		Model: {'id': '2cf4f3bdb37e4531bffc01b5dda502de', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.037, 'ICIR': 0.219, 'Rank IC': 0.005, 'Rank ICIR': 0.03}, 'data_train_vec': ['2025-04-24', '2026-01-23'], 'train_time_vec': ['2026-04-24', '2026-04-24'], 'rank_icir': '0.030', 'weight': '0.014'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260424_14 202051225362668902 (Recorders: 2/5)

	Recorder: be41a3ce92324d3f87e3ea1e6b1c6eab

		Model: {'id': 'be41a3ce92324d3f87e3ea1e6b1c6eab', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.017, 'Rank IC': 0.008, 'Rank ICIR': 0.065}, 'data_train_vec': ['2024-04-24', '2025-10-23'], 'train_time_vec': ['2026-04-24', '2026-04-24'], 'rank_icir': '0.065', 'weight': '0.030'}

	Recorder: 2ae297f08a37424db1d442c541e661b6

		Model: {'id': '2ae297f08a37424db1d442c541e661b6', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.053, 'ICIR': 0.436, 'Rank IC': 0.022, 'Rank ICIR': 0.161}, 'data_train_vec': ['2025-04-24', '2026-01-23'], 'train_time_vec': ['2026-04-24', '2026-04-24'], 'rank_icir': '0.161', 'weight': '0.073'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260424_14 611888774594308014 (Recorders: 3/5)

	Recorder: 1731f4b7d73b439aad302f099d945aa3

		Model: {'id': '1731f4b7d73b439aad302f099d945aa3', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.07, 'Rank IC': 0.041, 'Rank ICIR': 0.237}, 'data_train_vec': ['2023-04-24', '2025-07-23'], 'train_time_vec': ['2026-04-24', '2026-04-24'], 'rank_icir': '0.237', 'weight': '0.108'}

	Recorder: 61335ae8ece243ecb8407951235d9b9b

		Model: {'id': '61335ae8ece243ecb8407951235d9b9b', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.111, 'Rank IC': 0.032, 'Rank ICIR': 0.306}, 'data_train_vec': ['2024-04-24', '2025-10-23'], 'train_time_vec': ['2026-04-24', '2026-04-24'], 'rank_icir': '0.306', 'weight': '0.139'}

	Recorder: 31f6eb9948ae4019b6bf6544069f68e0

		Model: {'id': '31f6eb9948ae4019b6bf6544069f68e0', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.036, 'ICIR': 0.25, 'Rank IC': 0.005, 'Rank ICIR': 0.031}, 'data_train_vec': ['2025-04-24', '2026-01-23'], 'train_time_vec': ['2026-04-24', '2026-04-24'], 'rank_icir': '0.031', 'weight': '0.014'}
