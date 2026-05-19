# params 
 {'predict_dates': [{'start': '2026-05-19', 'end': '2026-05-19'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260519_18 892861471184324554 (Recorders: 4/5)

	Recorder: 36d18220d0a34bf3965d2d3aad8610ff

		Model: {'id': '36d18220d0a34bf3965d2d3aad8610ff', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.085, 'Rank IC': 0.022, 'Rank ICIR': 0.143}, 'data_train_vec': ['2022-05-19', '2025-05-18'], 'train_time_vec': ['2026-05-19', '2026-05-19'], 'rank_icir': '0.143', 'weight': '0.042'}

	Recorder: 3154864ea9b841418c1607efb18e7f01

		Model: {'id': '3154864ea9b841418c1607efb18e7f01', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.029, 'Rank IC': 0.032, 'Rank ICIR': 0.196}, 'data_train_vec': ['2023-05-19', '2025-08-18'], 'train_time_vec': ['2026-05-19', '2026-05-19'], 'rank_icir': '0.196', 'weight': '0.058'}

	Recorder: 9b6d9ece7f3d4435840fef9eb77a5a22

		Model: {'id': '9b6d9ece7f3d4435840fef9eb77a5a22', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.142, 'Rank IC': 0.01, 'Rank ICIR': 0.092}, 'data_train_vec': ['2024-05-19', '2025-11-18'], 'train_time_vec': ['2026-05-19', '2026-05-19'], 'rank_icir': '0.092', 'weight': '0.027'}

	Recorder: df9df857e94448428cd0ec8c30138e49

		Model: {'id': 'df9df857e94448428cd0ec8c30138e49', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.04, 'ICIR': 0.258, 'Rank IC': 0.037, 'Rank ICIR': 0.227}, 'data_train_vec': ['2025-05-19', '2026-02-18'], 'train_time_vec': ['2026-05-19', '2026-05-19'], 'rank_icir': '0.227', 'weight': '0.067'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260519_18 806343553734519947 (Recorders: 3/5)

	Recorder: 0f09a33f74ab4b66aee89fe90422ab97

		Model: {'id': '0f09a33f74ab4b66aee89fe90422ab97', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.164, 'Rank IC': 0.029, 'Rank ICIR': 0.243}, 'data_train_vec': ['2023-05-19', '2025-08-18'], 'train_time_vec': ['2026-05-19', '2026-05-19'], 'rank_icir': '0.243', 'weight': '0.072'}

	Recorder: fe508552529a4a3d84df19ea1cd13b2a

		Model: {'id': 'fe508552529a4a3d84df19ea1cd13b2a', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.133, 'Rank IC': 0.005, 'Rank ICIR': 0.05}, 'data_train_vec': ['2024-05-19', '2025-11-18'], 'train_time_vec': ['2026-05-19', '2026-05-19'], 'rank_icir': '0.050', 'weight': '0.015'}

	Recorder: fced4fa636db4af18515b2d55d369804

		Model: {'id': 'fced4fa636db4af18515b2d55d369804', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.09, 'ICIR': 0.577, 'Rank IC': 0.043, 'Rank ICIR': 0.257}, 'data_train_vec': ['2025-05-19', '2026-02-18'], 'train_time_vec': ['2026-05-19', '2026-05-19'], 'rank_icir': '0.257', 'weight': '0.076'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260519_15 522291309915013863 (Recorders: 4/5)

	Recorder: d50276ee8c5d4fc4a32190810507d66a

		Model: {'id': 'd50276ee8c5d4fc4a32190810507d66a', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.028, 'Rank IC': 0.028, 'Rank ICIR': 0.184}, 'data_train_vec': ['2021-05-19', '2025-02-18'], 'train_time_vec': ['2026-05-19', '2026-05-19'], 'rank_icir': '0.184', 'weight': '0.055'}

	Recorder: 18c81d93d60d41c1947c51e56e96210e

		Model: {'id': '18c81d93d60d41c1947c51e56e96210e', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.025, 'Rank IC': 0.035, 'Rank ICIR': 0.189}, 'data_train_vec': ['2022-05-19', '2025-05-18'], 'train_time_vec': ['2026-05-19', '2026-05-19'], 'rank_icir': '0.189', 'weight': '0.056'}

	Recorder: 6780a4e0278e44e3862701c3913272db

		Model: {'id': '6780a4e0278e44e3862701c3913272db', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.158, 'Rank IC': 0.041, 'Rank ICIR': 0.271}, 'data_train_vec': ['2023-05-19', '2025-08-18'], 'train_time_vec': ['2026-05-19', '2026-05-19'], 'rank_icir': '0.271', 'weight': '0.080'}

	Recorder: d60c69a62a3446588f3652c3aedde5c1

		Model: {'id': 'd60c69a62a3446588f3652c3aedde5c1', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.059, 'ICIR': 0.359, 'Rank IC': 0.028, 'Rank ICIR': 0.159}, 'data_train_vec': ['2025-05-19', '2026-02-18'], 'train_time_vec': ['2026-05-19', '2026-05-19'], 'rank_icir': '0.159', 'weight': '0.047'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260519_15 417039330286383089 (Recorders: 4/5)

	Recorder: 348603c2f7c842829c4f1dca2e56d0f0

		Model: {'id': '348603c2f7c842829c4f1dca2e56d0f0', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.063, 'Rank IC': 0.031, 'Rank ICIR': 0.276}, 'data_train_vec': ['2021-05-19', '2025-02-18'], 'train_time_vec': ['2026-05-19', '2026-05-19'], 'rank_icir': '0.276', 'weight': '0.082'}

	Recorder: 53831762a81d41238460f62be69537c2

		Model: {'id': '53831762a81d41238460f62be69537c2', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.091, 'Rank IC': 0.036, 'Rank ICIR': 0.325}, 'data_train_vec': ['2023-05-19', '2025-08-18'], 'train_time_vec': ['2026-05-19', '2026-05-19'], 'rank_icir': '0.325', 'weight': '0.096'}

	Recorder: 014f4a6d08ca40b592fa5564e3d0eba3

		Model: {'id': '014f4a6d08ca40b592fa5564e3d0eba3', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.044, 'Rank IC': 0.014, 'Rank ICIR': 0.123}, 'data_train_vec': ['2024-05-19', '2025-11-18'], 'train_time_vec': ['2026-05-19', '2026-05-19'], 'rank_icir': '0.123', 'weight': '0.036'}

	Recorder: 568045ee65e54326802578af282c16af

		Model: {'id': '568045ee65e54326802578af282c16af', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.071, 'ICIR': 0.513, 'Rank IC': 0.048, 'Rank ICIR': 0.3}, 'data_train_vec': ['2025-05-19', '2026-02-18'], 'train_time_vec': ['2026-05-19', '2026-05-19'], 'rank_icir': '0.300', 'weight': '0.089'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260519_15 401413499482469251 (Recorders: 2/5)

	Recorder: 4f3d23122f1945449b35dec26f90fe48

		Model: {'id': '4f3d23122f1945449b35dec26f90fe48', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.022, 'Rank IC': 0.024, 'Rank ICIR': 0.148}, 'data_train_vec': ['2023-05-19', '2025-08-18'], 'train_time_vec': ['2026-05-19', '2026-05-19'], 'rank_icir': '0.148', 'weight': '0.044'}

	Recorder: e0070c9cce404396920a7c9465f6b908

		Model: {'id': 'e0070c9cce404396920a7c9465f6b908', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.036, 'ICIR': 0.235, 'Rank IC': 0.031, 'Rank ICIR': 0.193}, 'data_train_vec': ['2025-05-19', '2026-02-18'], 'train_time_vec': ['2026-05-19', '2026-05-19'], 'rank_icir': '0.193', 'weight': '0.057'}
