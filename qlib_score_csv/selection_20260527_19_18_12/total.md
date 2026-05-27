# params 
 {'predict_dates': [{'start': '2026-05-27', 'end': '2026-05-27'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260527_18 307054243097089622 (Recorders: 3/5)

	Recorder: 19dad47828fe440f8a241bba396a6f4f

		Model: {'id': '19dad47828fe440f8a241bba396a6f4f', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.017, 'Rank IC': 0.021, 'Rank ICIR': 0.14}, 'data_train_vec': ['2022-05-27', '2025-05-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.140', 'weight': '0.043'}

	Recorder: 541ea47e4e6645e69b0b198b28e29782

		Model: {'id': '541ea47e4e6645e69b0b198b28e29782', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.018, 'Rank IC': 0.028, 'Rank ICIR': 0.16}, 'data_train_vec': ['2023-05-27', '2025-08-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.160', 'weight': '0.049'}

	Recorder: c7496760e4884d6e8e415b1844c67d6b

		Model: {'id': 'c7496760e4884d6e8e415b1844c67d6b', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.061, 'ICIR': 0.259, 'Rank IC': 0.032, 'Rank ICIR': 0.154}, 'data_train_vec': ['2025-05-27', '2026-02-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.154', 'weight': '0.047'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260527_18 220014906785107985 (Recorders: 3/5)

	Recorder: 0f7a292b059a4373a786bd091abfef3d

		Model: {'id': '0f7a292b059a4373a786bd091abfef3d', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.184, 'Rank IC': 0.031, 'Rank ICIR': 0.236}, 'data_train_vec': ['2023-05-27', '2025-08-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.236', 'weight': '0.072'}

	Recorder: e1436e6147b946d488b4bcb91ec20dc1

		Model: {'id': 'e1436e6147b946d488b4bcb91ec20dc1', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.11, 'Rank IC': 0.011, 'Rank ICIR': 0.107}, 'data_train_vec': ['2024-05-27', '2025-11-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.107', 'weight': '0.033'}

	Recorder: 6ba595d5763d4392a45c163c45a4b856

		Model: {'id': '6ba595d5763d4392a45c163c45a4b856', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.09, 'ICIR': 0.482, 'Rank IC': 0.047, 'Rank ICIR': 0.243}, 'data_train_vec': ['2025-05-27', '2026-02-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.243', 'weight': '0.074'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260527_16 978668373469940024 (Recorders: 4/5)

	Recorder: 5efd686dbb9343849e9060c5ccd40375

		Model: {'id': '5efd686dbb9343849e9060c5ccd40375', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.055, 'Rank IC': 0.034, 'Rank ICIR': 0.229}, 'data_train_vec': ['2021-05-27', '2025-02-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.229', 'weight': '0.070'}

	Recorder: 287e1d0f3dfc456490801e8841185f8c

		Model: {'id': '287e1d0f3dfc456490801e8841185f8c', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.063, 'Rank IC': 0.04, 'Rank ICIR': 0.226}, 'data_train_vec': ['2022-05-27', '2025-05-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.226', 'weight': '0.069'}

	Recorder: 1533894b095b4e568375f945f4c76702

		Model: {'id': '1533894b095b4e568375f945f4c76702', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.2, 'Rank IC': 0.043, 'Rank ICIR': 0.269}, 'data_train_vec': ['2023-05-27', '2025-08-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.269', 'weight': '0.082'}

	Recorder: 4d1cea3c5b0c48958c0e312bb9119907

		Model: {'id': '4d1cea3c5b0c48958c0e312bb9119907', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.054, 'ICIR': 0.313, 'Rank IC': 0.026, 'Rank ICIR': 0.141}, 'data_train_vec': ['2025-05-27', '2026-02-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.141', 'weight': '0.043'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260527_16 528351631336227336 (Recorders: 3/5)

	Recorder: 8ba68131edbd4fa9a71b50375f773e25

		Model: {'id': '8ba68131edbd4fa9a71b50375f773e25', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.06, 'Rank IC': 0.034, 'Rank ICIR': 0.292}, 'data_train_vec': ['2021-05-27', '2025-02-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.292', 'weight': '0.089'}

	Recorder: d90ebb3361784193ab36dea9ca2a0f82

		Model: {'id': 'd90ebb3361784193ab36dea9ca2a0f82', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.118, 'Rank IC': 0.036, 'Rank ICIR': 0.326}, 'data_train_vec': ['2023-05-27', '2025-08-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.326', 'weight': '0.100'}

	Recorder: faf44930e64a4f78b9ae202d9e793ee8

		Model: {'id': 'faf44930e64a4f78b9ae202d9e793ee8', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.092, 'ICIR': 0.507, 'Rank IC': 0.067, 'Rank ICIR': 0.319}, 'data_train_vec': ['2025-05-27', '2026-02-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.319', 'weight': '0.097'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260527_16 494232302728904227 (Recorders: 2/5)

	Recorder: 89da24e8feae4090bc3c77fef10eddaa

		Model: {'id': '89da24e8feae4090bc3c77fef10eddaa', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.09, 'Rank IC': 0.028, 'Rank ICIR': 0.174}, 'data_train_vec': ['2023-05-27', '2025-08-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.174', 'weight': '0.053'}

	Recorder: e29fd7dfeadf40bea9589a99fe8eaf79

		Model: {'id': 'e29fd7dfeadf40bea9589a99fe8eaf79', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.052, 'ICIR': 0.314, 'Rank IC': 0.042, 'Rank ICIR': 0.256}, 'data_train_vec': ['2025-05-27', '2026-02-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.256', 'weight': '0.078'}
