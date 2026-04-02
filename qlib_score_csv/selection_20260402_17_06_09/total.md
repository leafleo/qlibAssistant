# params 
 {'predict_dates': [{'start': '2026-04-02', 'end': '2026-04-02'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260402_16 497496756748140756 (Recorders: 4/5)

	Recorder: dcfa8ee75a6f475b8a35952b997d4ede

		Model: {'id': 'dcfa8ee75a6f475b8a35952b997d4ede', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.04, 'Rank IC': 0.033, 'Rank ICIR': 0.159}, 'data_train_vec': ['2021-04-02', '2025-01-01'], 'train_time_vec': ['2026-04-02', '2026-04-02'], 'rank_icir': '0.159', 'weight': '0.042'}

	Recorder: 043dcaf12a154bb8b16a1413e8994979

		Model: {'id': '043dcaf12a154bb8b16a1413e8994979', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.278, 'Rank IC': 0.053, 'Rank ICIR': 0.327}, 'data_train_vec': ['2023-04-02', '2025-07-01'], 'train_time_vec': ['2026-04-02', '2026-04-02'], 'rank_icir': '0.327', 'weight': '0.087'}

	Recorder: 055251dcee35499bace00dd93d91aa46

		Model: {'id': '055251dcee35499bace00dd93d91aa46', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.039, 'Rank IC': 0.04, 'Rank ICIR': 0.317}, 'data_train_vec': ['2024-04-02', '2025-10-01'], 'train_time_vec': ['2026-04-02', '2026-04-02'], 'rank_icir': '0.317', 'weight': '0.084'}

	Recorder: c4c4a56e01904dffb2f374a222e2d205

		Model: {'id': 'c4c4a56e01904dffb2f374a222e2d205', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.104, 'Rank IC': 0.002, 'Rank ICIR': 0.017}, 'data_train_vec': ['2025-04-02', '2026-01-01'], 'train_time_vec': ['2026-04-02', '2026-04-02'], 'rank_icir': '0.017', 'weight': '0.005'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260402_16 403407624308607502 (Recorders: 3/5)

	Recorder: 36278aa3e5bf4fce9a55bf6fa0cae60d

		Model: {'id': '36278aa3e5bf4fce9a55bf6fa0cae60d', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.017, 'Rank IC': 0.024, 'Rank ICIR': 0.155}, 'data_train_vec': ['2021-04-02', '2025-01-01'], 'train_time_vec': ['2026-04-02', '2026-04-02'], 'rank_icir': '0.155', 'weight': '0.041'}

	Recorder: dd7b4269f3cb417c9547ddbb968ab4ae

		Model: {'id': 'dd7b4269f3cb417c9547ddbb968ab4ae', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.037, 'Rank IC': 0.046, 'Rank ICIR': 0.267}, 'data_train_vec': ['2023-04-02', '2025-07-01'], 'train_time_vec': ['2026-04-02', '2026-04-02'], 'rank_icir': '0.267', 'weight': '0.071'}

	Recorder: 40958b14b1194bec9e4bd812751e8855

		Model: {'id': '40958b14b1194bec9e4bd812751e8855', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.246, 'Rank IC': 0.04, 'Rank ICIR': 0.353}, 'data_train_vec': ['2024-04-02', '2025-10-01'], 'train_time_vec': ['2026-04-02', '2026-04-02'], 'rank_icir': '0.353', 'weight': '0.094'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260402_14 282199131182846516 (Recorders: 3/5)

	Recorder: f7a864053ca14ca0b7c643c5bfa53c61

		Model: {'id': 'f7a864053ca14ca0b7c643c5bfa53c61', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.12, 'Rank IC': 0.04, 'Rank ICIR': 0.218}, 'data_train_vec': ['2021-04-02', '2025-01-01'], 'train_time_vec': ['2026-04-02', '2026-04-02'], 'rank_icir': '0.218', 'weight': '0.058'}

	Recorder: 7583aea8d90549adb7e2d68a85bb514c

		Model: {'id': '7583aea8d90549adb7e2d68a85bb514c', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.111, 'Rank IC': 0.053, 'Rank ICIR': 0.303}, 'data_train_vec': ['2023-04-02', '2025-07-01'], 'train_time_vec': ['2026-04-02', '2026-04-02'], 'rank_icir': '0.303', 'weight': '0.081'}

	Recorder: bacea8faf4ba433289fb8fa1fd66d6f3

		Model: {'id': 'bacea8faf4ba433289fb8fa1fd66d6f3', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.216, 'Rank IC': 0.035, 'Rank ICIR': 0.335}, 'data_train_vec': ['2024-04-02', '2025-10-01'], 'train_time_vec': ['2026-04-02', '2026-04-02'], 'rank_icir': '0.335', 'weight': '0.089'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260402_13 104849298877715641 (Recorders: 3/5)

	Recorder: 356973eadc5b4be5ba9fc630f1df75b6

		Model: {'id': '356973eadc5b4be5ba9fc630f1df75b6', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.107, 'Rank IC': 0.024, 'Rank ICIR': 0.193}, 'data_train_vec': ['2021-04-02', '2025-01-01'], 'train_time_vec': ['2026-04-02', '2026-04-02'], 'rank_icir': '0.193', 'weight': '0.051'}

	Recorder: a5b3c962b5ba41e999abab9d39095baa

		Model: {'id': 'a5b3c962b5ba41e999abab9d39095baa', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.03, 'Rank IC': 0.021, 'Rank ICIR': 0.178}, 'data_train_vec': ['2022-04-02', '2025-04-01'], 'train_time_vec': ['2026-04-02', '2026-04-02'], 'rank_icir': '0.178', 'weight': '0.047'}

	Recorder: ea57fa7f7dd549ef9643a15450bf13f7

		Model: {'id': 'ea57fa7f7dd549ef9643a15450bf13f7', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.113, 'Rank IC': 0.039, 'Rank ICIR': 0.327}, 'data_train_vec': ['2023-04-02', '2025-07-01'], 'train_time_vec': ['2026-04-02', '2026-04-02'], 'rank_icir': '0.327', 'weight': '0.087'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260402_13 126085085210372236 (Recorders: 4/5)

	Recorder: 9dfb722b3fd24599a1ac914001ca0740

		Model: {'id': '9dfb722b3fd24599a1ac914001ca0740', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.064, 'Rank IC': 0.03, 'Rank ICIR': 0.16}, 'data_train_vec': ['2021-04-02', '2025-01-01'], 'train_time_vec': ['2026-04-02', '2026-04-02'], 'rank_icir': '0.160', 'weight': '0.043'}

	Recorder: a5b80043b246477f8295f08ab8b2b38c

		Model: {'id': 'a5b80043b246477f8295f08ab8b2b38c', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.018, 'Rank IC': 0.026, 'Rank ICIR': 0.15}, 'data_train_vec': ['2022-04-02', '2025-04-01'], 'train_time_vec': ['2026-04-02', '2026-04-02'], 'rank_icir': '0.150', 'weight': '0.040'}

	Recorder: e1084aba7d02493da9ddf3c817b767e9

		Model: {'id': 'e1084aba7d02493da9ddf3c817b767e9', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.043, 'Rank IC': 0.043, 'Rank ICIR': 0.252}, 'data_train_vec': ['2023-04-02', '2025-07-01'], 'train_time_vec': ['2026-04-02', '2026-04-02'], 'rank_icir': '0.252', 'weight': '0.067'}

	Recorder: 214cfe328fb34687b0adb52eb1286e29

		Model: {'id': '214cfe328fb34687b0adb52eb1286e29', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.07, 'Rank IC': 0.005, 'Rank ICIR': 0.044}, 'data_train_vec': ['2025-04-02', '2026-01-01'], 'train_time_vec': ['2026-04-02', '2026-04-02'], 'rank_icir': '0.044', 'weight': '0.012'}
