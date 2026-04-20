# params 
 {'predict_dates': [{'start': '2026-04-20', 'end': '2026-04-20'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260420_16 656333761414616124 (Recorders: 3/5)

	Recorder: 2df362a32cef4b35b2e83b8bb94f9a5c

		Model: {'id': '2df362a32cef4b35b2e83b8bb94f9a5c', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.306, 'Rank IC': 0.04, 'Rank ICIR': 0.26}, 'data_train_vec': ['2023-04-20', '2025-07-19'], 'train_time_vec': ['2026-04-20', '2026-04-20'], 'rank_icir': '0.260', 'weight': '0.109'}

	Recorder: f0d1fd3cb7be497bb23e6920c6605543

		Model: {'id': 'f0d1fd3cb7be497bb23e6920c6605543', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.067, 'Rank IC': 0.034, 'Rank ICIR': 0.232}, 'data_train_vec': ['2024-04-20', '2025-10-19'], 'train_time_vec': ['2026-04-20', '2026-04-20'], 'rank_icir': '0.232', 'weight': '0.097'}

	Recorder: b690b207a340463da898ab919a010d5d

		Model: {'id': 'b690b207a340463da898ab919a010d5d', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.235, 'Rank IC': 0.011, 'Rank ICIR': 0.111}, 'data_train_vec': ['2025-04-20', '2026-01-19'], 'train_time_vec': ['2026-04-20', '2026-04-20'], 'rank_icir': '0.111', 'weight': '0.047'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260420_16 369344823803807180 (Recorders: 2/5)

	Recorder: a92c90523e4f41ebaee7db946e9cd3fc

		Model: {'id': 'a92c90523e4f41ebaee7db946e9cd3fc', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.186, 'Rank IC': 0.034, 'Rank ICIR': 0.287}, 'data_train_vec': ['2024-04-20', '2025-10-19'], 'train_time_vec': ['2026-04-20', '2026-04-20'], 'rank_icir': '0.287', 'weight': '0.120'}

	Recorder: a499e8bb906e47b2a4ee95661174d84e

		Model: {'id': 'a499e8bb906e47b2a4ee95661174d84e', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.207, 'Rank IC': 0.016, 'Rank ICIR': 0.117}, 'data_train_vec': ['2025-04-20', '2026-01-19'], 'train_time_vec': ['2026-04-20', '2026-04-20'], 'rank_icir': '0.117', 'weight': '0.049'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260420_14 660992908322716332 (Recorders: 3/5)

	Recorder: 538c95b45f4f467994823c5f91b2cbae

		Model: {'id': '538c95b45f4f467994823c5f91b2cbae', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.069, 'Rank IC': 0.043, 'Rank ICIR': 0.245}, 'data_train_vec': ['2023-04-20', '2025-07-19'], 'train_time_vec': ['2026-04-20', '2026-04-20'], 'rank_icir': '0.245', 'weight': '0.103'}

	Recorder: 239140c0e34148979ac3b46e0a5d2ced

		Model: {'id': '239140c0e34148979ac3b46e0a5d2ced', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.123, 'Rank IC': 0.018, 'Rank ICIR': 0.149}, 'data_train_vec': ['2024-04-20', '2025-10-19'], 'train_time_vec': ['2026-04-20', '2026-04-20'], 'rank_icir': '0.149', 'weight': '0.063'}

	Recorder: ccea56a70b69417bba9b9b736dc10bf2

		Model: {'id': 'ccea56a70b69417bba9b9b736dc10bf2', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.041, 'ICIR': 0.273, 'Rank IC': 0.028, 'Rank ICIR': 0.167}, 'data_train_vec': ['2025-04-20', '2026-01-19'], 'train_time_vec': ['2026-04-20', '2026-04-20'], 'rank_icir': '0.167', 'weight': '0.070'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260420_14 233733037340335176 (Recorders: 2/5)

	Recorder: c006c8e06d5e4f4cb18712a97a717718

		Model: {'id': 'c006c8e06d5e4f4cb18712a97a717718', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.032, 'Rank IC': 0.013, 'Rank ICIR': 0.106}, 'data_train_vec': ['2024-04-20', '2025-10-19'], 'train_time_vec': ['2026-04-20', '2026-04-20'], 'rank_icir': '0.106', 'weight': '0.044'}

	Recorder: 2a7bfbc62ec8446484ece9ff5cafeb1c

		Model: {'id': '2a7bfbc62ec8446484ece9ff5cafeb1c', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.068, 'ICIR': 0.465, 'Rank IC': 0.049, 'Rank ICIR': 0.332}, 'data_train_vec': ['2025-04-20', '2026-01-19'], 'train_time_vec': ['2026-04-20', '2026-04-20'], 'rank_icir': '0.332', 'weight': '0.139'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260420_14 191206030485996303 (Recorders: 2/5)

	Recorder: ad40098453ad4f38ba641b219b61e63a

		Model: {'id': 'ad40098453ad4f38ba641b219b61e63a', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.076, 'Rank IC': 0.03, 'Rank ICIR': 0.257}, 'data_train_vec': ['2024-04-20', '2025-10-19'], 'train_time_vec': ['2026-04-20', '2026-04-20'], 'rank_icir': '0.257', 'weight': '0.108'}

	Recorder: 3812b77763a74128a00af4f85ad3dc87

		Model: {'id': '3812b77763a74128a00af4f85ad3dc87', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.064, 'ICIR': 0.42, 'Rank IC': 0.019, 'Rank ICIR': 0.12}, 'data_train_vec': ['2025-04-20', '2026-01-19'], 'train_time_vec': ['2026-04-20', '2026-04-20'], 'rank_icir': '0.120', 'weight': '0.050'}
