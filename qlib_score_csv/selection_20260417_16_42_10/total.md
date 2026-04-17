# params 
 {'predict_dates': [{'start': '2026-04-17', 'end': '2026-04-17'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260417_16 172573683974524973 (Recorders: 3/5)

	Recorder: 6414302d46b94cb39d2bf7e5c6ab1753

		Model: {'id': '6414302d46b94cb39d2bf7e5c6ab1753', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.162, 'Rank IC': 0.033, 'Rank ICIR': 0.21}, 'data_train_vec': ['2023-04-17', '2025-07-16'], 'train_time_vec': ['2026-04-17', '2026-04-17'], 'rank_icir': '0.210', 'weight': '0.083'}

	Recorder: 48c1ee89686441fc891f2fd35676304c

		Model: {'id': '48c1ee89686441fc891f2fd35676304c', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.059, 'Rank IC': 0.034, 'Rank ICIR': 0.261}, 'data_train_vec': ['2024-04-17', '2025-10-16'], 'train_time_vec': ['2026-04-17', '2026-04-17'], 'rank_icir': '0.261', 'weight': '0.104'}

	Recorder: dfbfa5ca8e9c433b8e4dabb5e11609b6

		Model: {'id': 'dfbfa5ca8e9c433b8e4dabb5e11609b6', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.21, 'Rank IC': 0.033, 'Rank ICIR': 0.243}, 'data_train_vec': ['2025-04-17', '2026-01-16'], 'train_time_vec': ['2026-04-17', '2026-04-17'], 'rank_icir': '0.243', 'weight': '0.096'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260417_16 789816789005124690 (Recorders: 2/5)

	Recorder: 97355983f09a47ddb45f8f1a128d3e68

		Model: {'id': '97355983f09a47ddb45f8f1a128d3e68', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.157, 'Rank IC': 0.031, 'Rank ICIR': 0.243}, 'data_train_vec': ['2024-04-17', '2025-10-16'], 'train_time_vec': ['2026-04-17', '2026-04-17'], 'rank_icir': '0.243', 'weight': '0.096'}

	Recorder: bec74356baa24aaf8ef6eadb882770f1

		Model: {'id': 'bec74356baa24aaf8ef6eadb882770f1', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.045, 'ICIR': 0.379, 'Rank IC': 0.031, 'Rank ICIR': 0.244}, 'data_train_vec': ['2025-04-17', '2026-01-16'], 'train_time_vec': ['2026-04-17', '2026-04-17'], 'rank_icir': '0.244', 'weight': '0.097'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260417_14 584314690548677587 (Recorders: 4/5)

	Recorder: dcd08e9eeb8e48eeb4f7f5ee4c58570f

		Model: {'id': 'dcd08e9eeb8e48eeb4f7f5ee4c58570f', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.011, 'Rank IC': 0.022, 'Rank ICIR': 0.127}, 'data_train_vec': ['2021-04-17', '2025-01-16'], 'train_time_vec': ['2026-04-17', '2026-04-17'], 'rank_icir': '0.127', 'weight': '0.050'}

	Recorder: ba57644a771344c3b7d1d7a9ec95e2ae

		Model: {'id': 'ba57644a771344c3b7d1d7a9ec95e2ae', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.033, 'Rank IC': 0.035, 'Rank ICIR': 0.211}, 'data_train_vec': ['2023-04-17', '2025-07-16'], 'train_time_vec': ['2026-04-17', '2026-04-17'], 'rank_icir': '0.211', 'weight': '0.084'}

	Recorder: 9addfc557908470b88efdf5c9989708a

		Model: {'id': '9addfc557908470b88efdf5c9989708a', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.089, 'Rank IC': 0.02, 'Rank ICIR': 0.16}, 'data_train_vec': ['2024-04-17', '2025-10-16'], 'train_time_vec': ['2026-04-17', '2026-04-17'], 'rank_icir': '0.160', 'weight': '0.063'}

	Recorder: 683425601c364ab19d6d35644e908d82

		Model: {'id': '683425601c364ab19d6d35644e908d82', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.034, 'ICIR': 0.199, 'Rank IC': 0.026, 'Rank ICIR': 0.139}, 'data_train_vec': ['2025-04-17', '2026-01-16'], 'train_time_vec': ['2026-04-17', '2026-04-17'], 'rank_icir': '0.139', 'weight': '0.055'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260417_14 247761742338350208 (Recorders: 2/5)

	Recorder: e2182f6055e14d2d97141c5fec69f5e3

		Model: {'id': 'e2182f6055e14d2d97141c5fec69f5e3', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.008, 'Rank IC': 0.014, 'Rank ICIR': 0.123}, 'data_train_vec': ['2021-04-17', '2025-01-16'], 'train_time_vec': ['2026-04-17', '2026-04-17'], 'rank_icir': '0.123', 'weight': '0.049'}

	Recorder: c8e701c5b4df4e7b8e1f3054424adf9d

		Model: {'id': 'c8e701c5b4df4e7b8e1f3054424adf9d', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.048, 'ICIR': 0.338, 'Rank IC': 0.034, 'Rank ICIR': 0.24}, 'data_train_vec': ['2025-04-17', '2026-01-16'], 'train_time_vec': ['2026-04-17', '2026-04-17'], 'rank_icir': '0.240', 'weight': '0.095'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260417_13 537174840894781726 (Recorders: 2/5)

	Recorder: 5a51ad4368ea407297ae025734beaa8f

		Model: {'id': '5a51ad4368ea407297ae025734beaa8f', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.125, 'Rank IC': 0.028, 'Rank ICIR': 0.263}, 'data_train_vec': ['2024-04-17', '2025-10-16'], 'train_time_vec': ['2026-04-17', '2026-04-17'], 'rank_icir': '0.263', 'weight': '0.104'}

	Recorder: e1720cbb337f4eeb92e65dc1af56567b

		Model: {'id': 'e1720cbb337f4eeb92e65dc1af56567b', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.102, 'Rank IC': 0.009, 'Rank ICIR': 0.056}, 'data_train_vec': ['2025-04-17', '2026-01-16'], 'train_time_vec': ['2026-04-17', '2026-04-17'], 'rank_icir': '0.056', 'weight': '0.022'}
