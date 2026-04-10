# params 
 {'predict_dates': [{'start': '2026-04-10', 'end': '2026-04-10'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260410_16 671512074911330297 (Recorders: 3/5)

	Recorder: e765c8c41b1a4608883614166526f36a

		Model: {'id': 'e765c8c41b1a4608883614166526f36a', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.202, 'Rank IC': 0.036, 'Rank ICIR': 0.222}, 'data_train_vec': ['2023-04-10', '2025-07-09'], 'train_time_vec': ['2026-04-10', '2026-04-10'], 'rank_icir': '0.222', 'weight': '0.080'}

	Recorder: 177c11e10a1844bbb40fcb3ac01dfd1b

		Model: {'id': '177c11e10a1844bbb40fcb3ac01dfd1b', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.085, 'Rank IC': 0.028, 'Rank ICIR': 0.207}, 'data_train_vec': ['2024-04-10', '2025-10-09'], 'train_time_vec': ['2026-04-10', '2026-04-10'], 'rank_icir': '0.207', 'weight': '0.075'}

	Recorder: 9570c0af20a8497986ca88f8ecdd8605

		Model: {'id': '9570c0af20a8497986ca88f8ecdd8605', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.097, 'Rank IC': 0.003, 'Rank ICIR': 0.025}, 'data_train_vec': ['2025-04-10', '2026-01-09'], 'train_time_vec': ['2026-04-10', '2026-04-10'], 'rank_icir': '0.025', 'weight': '0.009'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260410_16 752445065853428824 (Recorders: 1/5)

	Recorder: 0e15060c9bfd4b7a9eded2c5cc9f731f

		Model: {'id': '0e15060c9bfd4b7a9eded2c5cc9f731f', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.326, 'Rank IC': 0.044, 'Rank ICIR': 0.391}, 'data_train_vec': ['2024-04-10', '2025-10-09'], 'train_time_vec': ['2026-04-10', '2026-04-10'], 'rank_icir': '0.391', 'weight': '0.141'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260410_13 568024662180036663 (Recorders: 3/5)

	Recorder: fdbc47c78eae4756aaccdb7b622c6301

		Model: {'id': 'fdbc47c78eae4756aaccdb7b622c6301', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.061, 'Rank IC': 0.026, 'Rank ICIR': 0.151}, 'data_train_vec': ['2021-04-10', '2025-01-09'], 'train_time_vec': ['2026-04-10', '2026-04-10'], 'rank_icir': '0.151', 'weight': '0.055'}

	Recorder: 28933ee9dec041dc825eb9b413fa8f90

		Model: {'id': '28933ee9dec041dc825eb9b413fa8f90', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.096, 'Rank IC': 0.047, 'Rank ICIR': 0.27}, 'data_train_vec': ['2023-04-10', '2025-07-09'], 'train_time_vec': ['2026-04-10', '2026-04-10'], 'rank_icir': '0.270', 'weight': '0.098'}

	Recorder: 8ae46f9431cb4048a411181f3732ba28

		Model: {'id': '8ae46f9431cb4048a411181f3732ba28', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.22, 'Rank IC': 0.023, 'Rank ICIR': 0.197}, 'data_train_vec': ['2024-04-10', '2025-10-09'], 'train_time_vec': ['2026-04-10', '2026-04-10'], 'rank_icir': '0.197', 'weight': '0.071'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260410_13 456358502123739570 (Recorders: 5/5)

	Recorder: 8686f1dd1a9e47bfb57a9e6166a8adf5

		Model: {'id': '8686f1dd1a9e47bfb57a9e6166a8adf5', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.088, 'Rank IC': 0.021, 'Rank ICIR': 0.17}, 'data_train_vec': ['2021-04-10', '2025-01-09'], 'train_time_vec': ['2026-04-10', '2026-04-10'], 'rank_icir': '0.170', 'weight': '0.062'}

	Recorder: ee16bad98ee747068771ac79edeac51a

		Model: {'id': 'ee16bad98ee747068771ac79edeac51a', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.017, 'Rank IC': 0.019, 'Rank ICIR': 0.167}, 'data_train_vec': ['2022-04-10', '2025-04-09'], 'train_time_vec': ['2026-04-10', '2026-04-10'], 'rank_icir': '0.167', 'weight': '0.060'}

	Recorder: 59c48e664100490a8460b3b80dcf67a6

		Model: {'id': '59c48e664100490a8460b3b80dcf67a6', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.12, 'Rank IC': 0.038, 'Rank ICIR': 0.327}, 'data_train_vec': ['2023-04-10', '2025-07-09'], 'train_time_vec': ['2026-04-10', '2026-04-10'], 'rank_icir': '0.327', 'weight': '0.118'}

	Recorder: f508d984b07c414283e90ea8153e48a4

		Model: {'id': 'f508d984b07c414283e90ea8153e48a4', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.055, 'Rank IC': 0.008, 'Rank ICIR': 0.064}, 'data_train_vec': ['2024-04-10', '2025-10-09'], 'train_time_vec': ['2026-04-10', '2026-04-10'], 'rank_icir': '0.064', 'weight': '0.023'}

	Recorder: 51aa8f39e30f4fe08500bbffbd91a392

		Model: {'id': '51aa8f39e30f4fe08500bbffbd91a392', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.081, 'Rank IC': 0.003, 'Rank ICIR': 0.019}, 'data_train_vec': ['2025-04-10', '2026-01-09'], 'train_time_vec': ['2026-04-10', '2026-04-10'], 'rank_icir': '0.019', 'weight': '0.007'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260410_13 296002091467114641 (Recorders: 3/5)

	Recorder: 5f0329bba8f14b238fa983616855d42c

		Model: {'id': '5f0329bba8f14b238fa983616855d42c', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.035, 'Rank IC': 0.018, 'Rank ICIR': 0.097}, 'data_train_vec': ['2021-04-10', '2025-01-09'], 'train_time_vec': ['2026-04-10', '2026-04-10'], 'rank_icir': '0.097', 'weight': '0.035'}

	Recorder: f9b1eed18f89428d9f8929b3dfa4dfee

		Model: {'id': 'f9b1eed18f89428d9f8929b3dfa4dfee', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.019, 'Rank IC': 0.031, 'Rank ICIR': 0.173}, 'data_train_vec': ['2023-04-10', '2025-07-09'], 'train_time_vec': ['2026-04-10', '2026-04-10'], 'rank_icir': '0.173', 'weight': '0.063'}

	Recorder: 44dbb38391a64a9b9ca3d310cfc58954

		Model: {'id': '44dbb38391a64a9b9ca3d310cfc58954', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.07, 'Rank IC': 0.034, 'Rank ICIR': 0.284}, 'data_train_vec': ['2024-04-10', '2025-10-09'], 'train_time_vec': ['2026-04-10', '2026-04-10'], 'rank_icir': '0.284', 'weight': '0.103'}
