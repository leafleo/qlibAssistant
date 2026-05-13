# params 
 {'predict_dates': [{'start': '2026-05-13', 'end': '2026-05-13'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260513_17 957819714258382854 (Recorders: 2/5)

	Recorder: 3e58899130b5439f89726bf87c1e6cbb

		Model: {'id': '3e58899130b5439f89726bf87c1e6cbb', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.02, 'Rank IC': 0.004, 'Rank ICIR': 0.032}, 'data_train_vec': ['2024-05-13', '2025-11-12'], 'train_time_vec': ['2026-05-13', '2026-05-13'], 'rank_icir': '0.032', 'weight': '0.013'}

	Recorder: fc47e063461d466ba4698b7c049cecac

		Model: {'id': 'fc47e063461d466ba4698b7c049cecac', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.085, 'ICIR': 0.779, 'Rank IC': 0.047, 'Rank ICIR': 0.425}, 'data_train_vec': ['2025-05-13', '2026-02-12'], 'train_time_vec': ['2026-05-13', '2026-05-13'], 'rank_icir': '0.425', 'weight': '0.167'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260513_17 584431750258286426 (Recorders: 3/5)

	Recorder: 4a406988a9174dd3a1a70b0af953f5d6

		Model: {'id': '4a406988a9174dd3a1a70b0af953f5d6', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.179, 'Rank IC': 0.024, 'Rank ICIR': 0.206}, 'data_train_vec': ['2023-05-13', '2025-08-12'], 'train_time_vec': ['2026-05-13', '2026-05-13'], 'rank_icir': '0.206', 'weight': '0.081'}

	Recorder: 28bd53814cee49e58f4e78a0aceeee1d

		Model: {'id': '28bd53814cee49e58f4e78a0aceeee1d', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.197, 'Rank IC': 0.003, 'Rank ICIR': 0.025}, 'data_train_vec': ['2024-05-13', '2025-11-12'], 'train_time_vec': ['2026-05-13', '2026-05-13'], 'rank_icir': '0.025', 'weight': '0.010'}

	Recorder: a8e1c37232d44d4bb63dc47bc075e834

		Model: {'id': 'a8e1c37232d44d4bb63dc47bc075e834', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.097, 'ICIR': 0.678, 'Rank IC': 0.045, 'Rank ICIR': 0.325}, 'data_train_vec': ['2025-05-13', '2026-02-12'], 'train_time_vec': ['2026-05-13', '2026-05-13'], 'rank_icir': '0.325', 'weight': '0.127'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260513_15 723222376117657010 (Recorders: 3/5)

	Recorder: bdac501e292a4d20b3b2242d54a3843d

		Model: {'id': 'bdac501e292a4d20b3b2242d54a3843d', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.069, 'Rank IC': 0.027, 'Rank ICIR': 0.18}, 'data_train_vec': ['2023-05-13', '2025-08-12'], 'train_time_vec': ['2026-05-13', '2026-05-13'], 'rank_icir': '0.180', 'weight': '0.071'}

	Recorder: 32147420af0c4431a959369843c9a039

		Model: {'id': '32147420af0c4431a959369843c9a039', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.009, 'Rank IC': 0.003, 'Rank ICIR': 0.021}, 'data_train_vec': ['2024-05-13', '2025-11-12'], 'train_time_vec': ['2026-05-13', '2026-05-13'], 'rank_icir': '0.021', 'weight': '0.008'}

	Recorder: 9c2edad08d994cf1a8fc5ceb1401c6db

		Model: {'id': '9c2edad08d994cf1a8fc5ceb1401c6db', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.077, 'ICIR': 0.612, 'Rank IC': 0.04, 'Rank ICIR': 0.317}, 'data_train_vec': ['2025-05-13', '2026-02-12'], 'train_time_vec': ['2026-05-13', '2026-05-13'], 'rank_icir': '0.317', 'weight': '0.124'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260513_15 831235408708703758 (Recorders: 3/5)

	Recorder: e4ab2d978b0a48c0b849f3ea34dd5b8f

		Model: {'id': 'e4ab2d978b0a48c0b849f3ea34dd5b8f', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.017, 'Rank IC': 0.026, 'Rank ICIR': 0.234}, 'data_train_vec': ['2023-05-13', '2025-08-12'], 'train_time_vec': ['2026-05-13', '2026-05-13'], 'rank_icir': '0.234', 'weight': '0.092'}

	Recorder: 9a9f7606a29c46e5be67fdf4629f07b9

		Model: {'id': '9a9f7606a29c46e5be67fdf4629f07b9', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.124, 'Rank IC': 0.024, 'Rank ICIR': 0.21}, 'data_train_vec': ['2024-05-13', '2025-11-12'], 'train_time_vec': ['2026-05-13', '2026-05-13'], 'rank_icir': '0.210', 'weight': '0.082'}

	Recorder: c943d4f61fe1404096c354f26af4de5a

		Model: {'id': 'c943d4f61fe1404096c354f26af4de5a', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.072, 'ICIR': 0.608, 'Rank IC': 0.045, 'Rank ICIR': 0.366}, 'data_train_vec': ['2025-05-13', '2026-02-12'], 'train_time_vec': ['2026-05-13', '2026-05-13'], 'rank_icir': '0.366', 'weight': '0.144'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260513_14 923075767982375036 (Recorders: 1/5)

	Recorder: 2e725a1498024a7b92dad05cd7eb6453

		Model: {'id': '2e725a1498024a7b92dad05cd7eb6453', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.048, 'ICIR': 0.407, 'Rank IC': 0.022, 'Rank ICIR': 0.209}, 'data_train_vec': ['2025-05-13', '2026-02-12'], 'train_time_vec': ['2026-05-13', '2026-05-13'], 'rank_icir': '0.209', 'weight': '0.082'}
