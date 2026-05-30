# params 
 {'predict_dates': [{'start': '2026-05-29', 'end': '2026-05-29'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260530_16 257278961161128302 (Recorders: 4/5)

	Recorder: 25f3a7b8c03349ea9e8a674828cf3e71

		Model: {'id': '25f3a7b8c03349ea9e8a674828cf3e71', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.012, 'Rank IC': 0.022, 'Rank ICIR': 0.15}, 'data_train_vec': ['2021-05-28', '2025-02-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.150', 'weight': '0.054'}

	Recorder: 6f70cd162e584ef181745d223e5db7fa

		Model: {'id': '6f70cd162e584ef181745d223e5db7fa', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.008, 'Rank IC': 0.019, 'Rank ICIR': 0.137}, 'data_train_vec': ['2022-05-30', '2025-05-29'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.137', 'weight': '0.050'}

	Recorder: 6ff1d289d155480884054fb016db8e08

		Model: {'id': '6ff1d289d155480884054fb016db8e08', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.034, 'ICIR': 0.31, 'Rank IC': 0.029, 'Rank ICIR': 0.196}, 'data_train_vec': ['2023-05-28', '2025-08-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.196', 'weight': '0.071'}

	Recorder: 92c49d6ffbdc412fb9404fc2938d4418

		Model: {'id': '92c49d6ffbdc412fb9404fc2938d4418', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.048, 'ICIR': 0.245, 'Rank IC': 0.012, 'Rank ICIR': 0.058}, 'data_train_vec': ['2025-05-28', '2026-02-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.058', 'weight': '0.021'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260530_16 463583727792465746 (Recorders: 3/5)

	Recorder: 3231f0374a7742759c31a5a704613286

		Model: {'id': '3231f0374a7742759c31a5a704613286', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.16, 'Rank IC': 0.027, 'Rank ICIR': 0.189}, 'data_train_vec': ['2023-05-28', '2025-08-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.189', 'weight': '0.068'}

	Recorder: 2303242575db40ceb163860e20ba2f85

		Model: {'id': '2303242575db40ceb163860e20ba2f85', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.081, 'Rank IC': 0.009, 'Rank ICIR': 0.083}, 'data_train_vec': ['2024-05-30', '2025-11-29'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.083', 'weight': '0.030'}

	Recorder: 2c4cbb1c68a140398eef90f0a65fefc8

		Model: {'id': '2c4cbb1c68a140398eef90f0a65fefc8', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.076, 'ICIR': 0.34, 'Rank IC': 0.03, 'Rank ICIR': 0.135}, 'data_train_vec': ['2025-05-28', '2026-02-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.135', 'weight': '0.049'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260530_14 515536419922867314 (Recorders: 3/5)

	Recorder: 301677fd26a84115b84075b3cab3ade8

		Model: {'id': '301677fd26a84115b84075b3cab3ade8', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.042, 'Rank IC': 0.032, 'Rank ICIR': 0.216}, 'data_train_vec': ['2021-05-28', '2025-02-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.216', 'weight': '0.078'}

	Recorder: 1310739e01884cbf950d939194a8bab6

		Model: {'id': '1310739e01884cbf950d939194a8bab6', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.026, 'Rank IC': 0.037, 'Rank ICIR': 0.205}, 'data_train_vec': ['2022-05-30', '2025-05-29'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.205', 'weight': '0.074'}

	Recorder: 7eca48294c6a411985f9194ff5a92a6c

		Model: {'id': '7eca48294c6a411985f9194ff5a92a6c', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.221, 'Rank IC': 0.041, 'Rank ICIR': 0.277}, 'data_train_vec': ['2023-05-28', '2025-08-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.277', 'weight': '0.100'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260530_14 548363538823849834 (Recorders: 4/5)

	Recorder: d8b3655f49ab40a684aef6722cc7c6fc

		Model: {'id': 'd8b3655f49ab40a684aef6722cc7c6fc', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.064, 'Rank IC': 0.035, 'Rank ICIR': 0.304}, 'data_train_vec': ['2021-05-28', '2025-02-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.304', 'weight': '0.110'}

	Recorder: 76f9b6238f3543b2b28aa30f9ef8d78f

		Model: {'id': '76f9b6238f3543b2b28aa30f9ef8d78f', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.097, 'Rank IC': 0.031, 'Rank ICIR': 0.281}, 'data_train_vec': ['2023-05-28', '2025-08-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.281', 'weight': '0.102'}

	Recorder: 2ebf0cd778a64a00b1d5cee4e2c7de16

		Model: {'id': '2ebf0cd778a64a00b1d5cee4e2c7de16', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.029, 'Rank IC': 0.011, 'Rank ICIR': 0.083}, 'data_train_vec': ['2024-05-30', '2025-11-29'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.083', 'weight': '0.030'}

	Recorder: 11954a32eaad4fdc8ce18a4edd1fb6cc

		Model: {'id': '11954a32eaad4fdc8ce18a4edd1fb6cc', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.051, 'ICIR': 0.242, 'Rank IC': 0.029, 'Rank ICIR': 0.124}, 'data_train_vec': ['2025-05-28', '2026-02-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.124', 'weight': '0.045'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260530_14 954475686299622072 (Recorders: 3/5)

	Recorder: 5847baa7992646489eb365bce4ab2627

		Model: {'id': '5847baa7992646489eb365bce4ab2627', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.025, 'Rank IC': 0.02, 'Rank ICIR': 0.122}, 'data_train_vec': ['2021-05-28', '2025-02-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.122', 'weight': '0.044'}

	Recorder: d8f04364444a4500afeecb9af1f0bdc0

		Model: {'id': 'd8f04364444a4500afeecb9af1f0bdc0', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.036, 'Rank IC': 0.026, 'Rank ICIR': 0.168}, 'data_train_vec': ['2023-05-28', '2025-08-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.168', 'weight': '0.061'}

	Recorder: 38b5f02cd5d24d21925210e9f139592b

		Model: {'id': '38b5f02cd5d24d21925210e9f139592b', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.086, 'Rank IC': 0.006, 'Rank ICIR': 0.037}, 'data_train_vec': ['2025-05-28', '2026-02-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.037', 'weight': '0.013'}
