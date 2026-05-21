# params 
 {'predict_dates': [{'start': '2026-05-21', 'end': '2026-05-21'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260521_18 829796698441994191 (Recorders: 3/5)

	Recorder: b49c474acfe34c72a08b55458ce04d92

		Model: {'id': 'b49c474acfe34c72a08b55458ce04d92', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.035, 'Rank IC': 0.018, 'Rank ICIR': 0.133}, 'data_train_vec': ['2022-05-21', '2025-05-20'], 'train_time_vec': ['2026-05-21', '2026-05-21'], 'rank_icir': '0.133', 'weight': '0.049'}

	Recorder: 573d6f2630944af6aa63d544e43d4ae2

		Model: {'id': '573d6f2630944af6aa63d544e43d4ae2', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.077, 'Rank IC': 0.024, 'Rank ICIR': 0.141}, 'data_train_vec': ['2023-05-21', '2025-08-20'], 'train_time_vec': ['2026-05-21', '2026-05-21'], 'rank_icir': '0.141', 'weight': '0.052'}

	Recorder: d6749a45a1694d20a6fc46ab87826e4c

		Model: {'id': 'd6749a45a1694d20a6fc46ab87826e4c', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.046, 'ICIR': 0.256, 'Rank IC': 0.014, 'Rank ICIR': 0.088}, 'data_train_vec': ['2025-05-21', '2026-02-20'], 'train_time_vec': ['2026-05-21', '2026-05-21'], 'rank_icir': '0.088', 'weight': '0.032'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260521_18 293472877906006734 (Recorders: 3/5)

	Recorder: 80479c8829134680955f691ff1dd7002

		Model: {'id': '80479c8829134680955f691ff1dd7002', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.081, 'Rank IC': 0.02, 'Rank ICIR': 0.156}, 'data_train_vec': ['2023-05-21', '2025-08-20'], 'train_time_vec': ['2026-05-21', '2026-05-21'], 'rank_icir': '0.156', 'weight': '0.057'}

	Recorder: 1b0a594df1a346e9a61b6cd6817b5b48

		Model: {'id': '1b0a594df1a346e9a61b6cd6817b5b48', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.194, 'Rank IC': 0.01, 'Rank ICIR': 0.097}, 'data_train_vec': ['2024-05-21', '2025-11-20'], 'train_time_vec': ['2026-05-21', '2026-05-21'], 'rank_icir': '0.097', 'weight': '0.036'}

	Recorder: d635708e267f4fe3a57ad356209ae40d

		Model: {'id': 'd635708e267f4fe3a57ad356209ae40d', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.066, 'ICIR': 0.378, 'Rank IC': 0.022, 'Rank ICIR': 0.117}, 'data_train_vec': ['2025-05-21', '2026-02-20'], 'train_time_vec': ['2026-05-21', '2026-05-21'], 'rank_icir': '0.117', 'weight': '0.043'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260521_16 564211305411825907 (Recorders: 4/5)

	Recorder: cfbe3c5d0b8a4b80ba7d0b30d9763eeb

		Model: {'id': 'cfbe3c5d0b8a4b80ba7d0b30d9763eeb', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.048, 'Rank IC': 0.031, 'Rank ICIR': 0.199}, 'data_train_vec': ['2021-05-21', '2025-02-20'], 'train_time_vec': ['2026-05-21', '2026-05-21'], 'rank_icir': '0.199', 'weight': '0.073'}

	Recorder: f7e54c4986db439ea3d1919f2e80528d

		Model: {'id': 'f7e54c4986db439ea3d1919f2e80528d', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.03, 'Rank IC': 0.035, 'Rank ICIR': 0.19}, 'data_train_vec': ['2022-05-21', '2025-05-20'], 'train_time_vec': ['2026-05-21', '2026-05-21'], 'rank_icir': '0.190', 'weight': '0.070'}

	Recorder: 826ff18448bd4683a2614aeeb88595e1

		Model: {'id': '826ff18448bd4683a2614aeeb88595e1', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.148, 'Rank IC': 0.038, 'Rank ICIR': 0.255}, 'data_train_vec': ['2023-05-21', '2025-08-20'], 'train_time_vec': ['2026-05-21', '2026-05-21'], 'rank_icir': '0.255', 'weight': '0.094'}

	Recorder: 098c3398601641e8827738cd8a9da176

		Model: {'id': '098c3398601641e8827738cd8a9da176', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.046, 'ICIR': 0.286, 'Rank IC': 0.015, 'Rank ICIR': 0.086}, 'data_train_vec': ['2025-05-21', '2026-02-20'], 'train_time_vec': ['2026-05-21', '2026-05-21'], 'rank_icir': '0.086', 'weight': '0.032'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260521_15 468665969258551066 (Recorders: 3/5)

	Recorder: af9a831273e9461d90c7c3d808587b8f

		Model: {'id': 'af9a831273e9461d90c7c3d808587b8f', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.06, 'Rank IC': 0.029, 'Rank ICIR': 0.264}, 'data_train_vec': ['2021-05-21', '2025-02-20'], 'train_time_vec': ['2026-05-21', '2026-05-21'], 'rank_icir': '0.264', 'weight': '0.097'}

	Recorder: be58d462d3e346feac387754771bbd69

		Model: {'id': 'be58d462d3e346feac387754771bbd69', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.074, 'Rank IC': 0.033, 'Rank ICIR': 0.314}, 'data_train_vec': ['2023-05-21', '2025-08-20'], 'train_time_vec': ['2026-05-21', '2026-05-21'], 'rank_icir': '0.314', 'weight': '0.116'}

	Recorder: ca1c59eebd6a4cd4ac3edc442a73a136

		Model: {'id': 'ca1c59eebd6a4cd4ac3edc442a73a136', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.069, 'ICIR': 0.457, 'Rank IC': 0.044, 'Rank ICIR': 0.253}, 'data_train_vec': ['2025-05-21', '2026-02-20'], 'train_time_vec': ['2026-05-21', '2026-05-21'], 'rank_icir': '0.253', 'weight': '0.093'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260521_15 183619963266184368 (Recorders: 2/5)

	Recorder: 252cb05fd4154305949c52dd52d74ded

		Model: {'id': '252cb05fd4154305949c52dd52d74ded', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.095, 'Rank IC': 0.032, 'Rank ICIR': 0.222}, 'data_train_vec': ['2023-05-21', '2025-08-20'], 'train_time_vec': ['2026-05-21', '2026-05-21'], 'rank_icir': '0.222', 'weight': '0.082'}

	Recorder: a0e1a77afeeb4395ab3bcdfdece5e991

		Model: {'id': 'a0e1a77afeeb4395ab3bcdfdece5e991', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.044, 'ICIR': 0.307, 'Rank IC': 0.028, 'Rank ICIR': 0.201}, 'data_train_vec': ['2025-05-21', '2026-02-20'], 'train_time_vec': ['2026-05-21', '2026-05-21'], 'rank_icir': '0.201', 'weight': '0.074'}
