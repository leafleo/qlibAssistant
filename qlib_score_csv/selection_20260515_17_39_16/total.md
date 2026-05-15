# params 
 {'predict_dates': [{'start': '2026-05-15', 'end': '2026-05-15'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260515_17 834444936592660368 (Recorders: 3/5)

	Recorder: d1b224bdb40f417bb6849da7597eb49b

		Model: {'id': 'd1b224bdb40f417bb6849da7597eb49b', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.032, 'Rank IC': 0.02, 'Rank ICIR': 0.128}, 'data_train_vec': ['2022-05-15', '2025-05-14'], 'train_time_vec': ['2026-05-15', '2026-05-15'], 'rank_icir': '0.128', 'weight': '0.056'}

	Recorder: 0cd51b3d37c24dacae5be7324eadc4e1

		Model: {'id': '0cd51b3d37c24dacae5be7324eadc4e1', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.017, 'Rank IC': 0.022, 'Rank ICIR': 0.143}, 'data_train_vec': ['2023-05-15', '2025-08-14'], 'train_time_vec': ['2026-05-15', '2026-05-15'], 'rank_icir': '0.143', 'weight': '0.063'}

	Recorder: 3185384342d94bf6896660d162c94a7f

		Model: {'id': '3185384342d94bf6896660d162c94a7f', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.081, 'ICIR': 0.54, 'Rank IC': 0.043, 'Rank ICIR': 0.267}, 'data_train_vec': ['2025-05-15', '2026-02-14'], 'train_time_vec': ['2026-05-15', '2026-05-15'], 'rank_icir': '0.267', 'weight': '0.117'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260515_17 206360147058595545 (Recorders: 2/5)

	Recorder: 3ccceec8cabc423db8bc2f2604f8ea2f

		Model: {'id': '3ccceec8cabc423db8bc2f2604f8ea2f', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.165, 'Rank IC': 0.021, 'Rank ICIR': 0.181}, 'data_train_vec': ['2023-05-15', '2025-08-14'], 'train_time_vec': ['2026-05-15', '2026-05-15'], 'rank_icir': '0.181', 'weight': '0.080'}

	Recorder: 9ae92d9fd68a45cb96da42022d26fc4f

		Model: {'id': '9ae92d9fd68a45cb96da42022d26fc4f', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.079, 'ICIR': 0.503, 'Rank IC': 0.026, 'Rank ICIR': 0.156}, 'data_train_vec': ['2025-05-15', '2026-02-14'], 'train_time_vec': ['2026-05-15', '2026-05-15'], 'rank_icir': '0.156', 'weight': '0.069'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260515_14 349876516005981064 (Recorders: 3/5)

	Recorder: 1a1ed52b2ed441d7a8172b9463c8e1b8

		Model: {'id': '1a1ed52b2ed441d7a8172b9463c8e1b8', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.029, 'Rank IC': 0.032, 'Rank ICIR': 0.173}, 'data_train_vec': ['2022-05-15', '2025-05-14'], 'train_time_vec': ['2026-05-15', '2026-05-15'], 'rank_icir': '0.173', 'weight': '0.076'}

	Recorder: 214d71f52fb54214922c82b349d8133b

		Model: {'id': '214d71f52fb54214922c82b349d8133b', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.114, 'Rank IC': 0.036, 'Rank ICIR': 0.231}, 'data_train_vec': ['2023-05-15', '2025-08-14'], 'train_time_vec': ['2026-05-15', '2026-05-15'], 'rank_icir': '0.231', 'weight': '0.102'}

	Recorder: cdc365b7aec04b94b1985504d62a2a16

		Model: {'id': 'cdc365b7aec04b94b1985504d62a2a16', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.061, 'ICIR': 0.407, 'Rank IC': 0.025, 'Rank ICIR': 0.15}, 'data_train_vec': ['2025-05-15', '2026-02-14'], 'train_time_vec': ['2026-05-15', '2026-05-15'], 'rank_icir': '0.150', 'weight': '0.066'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260515_14 488539974530980522 (Recorders: 3/5)

	Recorder: 0f88fa579409492f8c527e3a95614812

		Model: {'id': '0f88fa579409492f8c527e3a95614812', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.037, 'Rank IC': 0.029, 'Rank ICIR': 0.266}, 'data_train_vec': ['2023-05-15', '2025-08-14'], 'train_time_vec': ['2026-05-15', '2026-05-15'], 'rank_icir': '0.266', 'weight': '0.117'}

	Recorder: 33fc3c8d37f54f14babf80fd4ec1adea

		Model: {'id': '33fc3c8d37f54f14babf80fd4ec1adea', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.042, 'Rank IC': 0.016, 'Rank ICIR': 0.142}, 'data_train_vec': ['2024-05-15', '2025-11-14'], 'train_time_vec': ['2026-05-15', '2026-05-15'], 'rank_icir': '0.142', 'weight': '0.062'}

	Recorder: 6bfa14abcd944e39abe51d409a53d715

		Model: {'id': '6bfa14abcd944e39abe51d409a53d715', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.075, 'ICIR': 0.594, 'Rank IC': 0.044, 'Rank ICIR': 0.313}, 'data_train_vec': ['2025-05-15', '2026-02-14'], 'train_time_vec': ['2026-05-15', '2026-05-15'], 'rank_icir': '0.313', 'weight': '0.138'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260515_14 677374297471968695 (Recorders: 1/5)

	Recorder: a7d412f8caa349abbce533b41df8c707

		Model: {'id': 'a7d412f8caa349abbce533b41df8c707', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.044, 'ICIR': 0.337, 'Rank IC': 0.017, 'Rank ICIR': 0.123}, 'data_train_vec': ['2025-05-15', '2026-02-14'], 'train_time_vec': ['2026-05-15', '2026-05-15'], 'rank_icir': '0.123', 'weight': '0.054'}
