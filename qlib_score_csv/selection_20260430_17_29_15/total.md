# params 
 {'predict_dates': [{'start': '2026-04-30', 'end': '2026-04-30'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260430_17 845086777045940132 (Recorders: 2/5)

	Recorder: 20e4cf1df1474844b87294a4cdea6754

		Model: {'id': '20e4cf1df1474844b87294a4cdea6754', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.06, 'Rank IC': 0.013, 'Rank ICIR': 0.127}, 'data_train_vec': ['2024-04-28', '2025-10-27'], 'train_time_vec': ['2026-04-30', '2026-04-30'], 'rank_icir': '0.127', 'weight': '0.086'}

	Recorder: be909a90fadd49d986c8b28b060e30b5

		Model: {'id': 'be909a90fadd49d986c8b28b060e30b5', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.047, 'ICIR': 0.406, 'Rank IC': 0.019, 'Rank ICIR': 0.167}, 'data_train_vec': ['2025-04-30', '2026-01-29'], 'train_time_vec': ['2026-04-30', '2026-04-30'], 'rank_icir': '0.167', 'weight': '0.113'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260430_16 914352583653442527 (Recorders: 2/5)

	Recorder: 205c0dceacd34d62a1e29110dbc9c003

		Model: {'id': '205c0dceacd34d62a1e29110dbc9c003', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.058, 'Rank IC': 0.01, 'Rank ICIR': 0.086}, 'data_train_vec': ['2024-04-28', '2025-10-27'], 'train_time_vec': ['2026-04-30', '2026-04-30'], 'rank_icir': '0.086', 'weight': '0.058'}

	Recorder: 040ac797054b4780a8db24c291a0edee

		Model: {'id': '040ac797054b4780a8db24c291a0edee', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.075, 'ICIR': 0.643, 'Rank IC': 0.035, 'Rank ICIR': 0.287}, 'data_train_vec': ['2025-04-30', '2026-01-29'], 'train_time_vec': ['2026-04-30', '2026-04-30'], 'rank_icir': '0.287', 'weight': '0.194'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260430_14 898250584401932280 (Recorders: 2/5)

	Recorder: 40c4366d85134575a8ac37ffa8267117

		Model: {'id': '40c4366d85134575a8ac37ffa8267117', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.103, 'Rank IC': 0.002, 'Rank ICIR': 0.019}, 'data_train_vec': ['2024-04-28', '2025-10-27'], 'train_time_vec': ['2026-04-30', '2026-04-30'], 'rank_icir': '0.019', 'weight': '0.013'}

	Recorder: 0119fc199b5a4de09469fb567167ec07

		Model: {'id': '0119fc199b5a4de09469fb567167ec07', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.047, 'ICIR': 0.36, 'Rank IC': 0.017, 'Rank ICIR': 0.114}, 'data_train_vec': ['2025-04-30', '2026-01-29'], 'train_time_vec': ['2026-04-30', '2026-04-30'], 'rank_icir': '0.114', 'weight': '0.077'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260430_14 150770408382767950 (Recorders: 2/5)

	Recorder: 9f5c054ecc1c48f785e1c931d96955aa

		Model: {'id': '9f5c054ecc1c48f785e1c931d96955aa', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.022, 'Rank IC': 0.009, 'Rank ICIR': 0.072}, 'data_train_vec': ['2024-04-28', '2025-10-27'], 'train_time_vec': ['2026-04-30', '2026-04-30'], 'rank_icir': '0.072', 'weight': '0.049'}

	Recorder: 852807deac7d4d679ead95d2f98e67c2

		Model: {'id': '852807deac7d4d679ead95d2f98e67c2', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.057, 'ICIR': 0.598, 'Rank IC': 0.03, 'Rank ICIR': 0.273}, 'data_train_vec': ['2025-04-30', '2026-01-29'], 'train_time_vec': ['2026-04-30', '2026-04-30'], 'rank_icir': '0.273', 'weight': '0.184'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260430_14 531532378571340944 (Recorders: 3/5)

	Recorder: abe4272b068440988ce069a6abf56007

		Model: {'id': 'abe4272b068440988ce069a6abf56007', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.043, 'Rank IC': 0.013, 'Rank ICIR': 0.075}, 'data_train_vec': ['2021-04-30', '2025-01-29'], 'train_time_vec': ['2026-04-30', '2026-04-30'], 'rank_icir': '0.075', 'weight': '0.051'}

	Recorder: f80204a58d3a49018dbd391249c14515

		Model: {'id': 'f80204a58d3a49018dbd391249c14515', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.049, 'Rank IC': 0.017, 'Rank ICIR': 0.145}, 'data_train_vec': ['2024-04-28', '2025-10-27'], 'train_time_vec': ['2026-04-30', '2026-04-30'], 'rank_icir': '0.145', 'weight': '0.098'}

	Recorder: 3d0f4a185b3242a8bf86d6e51e62208e

		Model: {'id': '3d0f4a185b3242a8bf86d6e51e62208e', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.271, 'Rank IC': 0.01, 'Rank ICIR': 0.118}, 'data_train_vec': ['2025-04-30', '2026-01-29'], 'train_time_vec': ['2026-04-30', '2026-04-30'], 'rank_icir': '0.118', 'weight': '0.080'}
