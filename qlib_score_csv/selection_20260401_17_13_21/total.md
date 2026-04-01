# params 
 {'predict_dates': [{'start': '2026-04-01', 'end': '2026-04-01'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260401_16 889912124563748560 (Recorders: 3/5)

	Recorder: 5ff322a452f9451b8f49a0f0d510bbf9

		Model: {'id': '5ff322a452f9451b8f49a0f0d510bbf9', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.208, 'Rank IC': 0.052, 'Rank ICIR': 0.304}, 'data_train_vec': ['2023-04-01', '2025-06-30'], 'train_time_vec': ['2026-04-01', '2026-04-01'], 'rank_icir': '0.304', 'weight': '0.093'}

	Recorder: b113ede071cd4c4f83a3cadca71137e4

		Model: {'id': 'b113ede071cd4c4f83a3cadca71137e4', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.135, 'Rank IC': 0.05, 'Rank ICIR': 0.356}, 'data_train_vec': ['2024-04-01', '2025-09-30'], 'train_time_vec': ['2026-04-01', '2026-04-01'], 'rank_icir': '0.356', 'weight': '0.109'}

	Recorder: 4d7c212cc8c1458abcddc70f639e2ef5

		Model: {'id': '4d7c212cc8c1458abcddc70f639e2ef5', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.14, 'Rank IC': 0.009, 'Rank ICIR': 0.069}, 'data_train_vec': ['2025-04-01', '2025-12-31'], 'train_time_vec': ['2026-04-01', '2026-04-01'], 'rank_icir': '0.069', 'weight': '0.021'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260401_16 717206506912320214 (Recorders: 3/5)

	Recorder: 92dfbaf7e2624448b8c02ccd8b36076f

		Model: {'id': '92dfbaf7e2624448b8c02ccd8b36076f', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.039, 'Rank IC': 0.027, 'Rank ICIR': 0.158}, 'data_train_vec': ['2021-04-01', '2024-12-31'], 'train_time_vec': ['2026-04-01', '2026-04-01'], 'rank_icir': '0.158', 'weight': '0.048'}

	Recorder: 0c9a88010e514b75a768aa6d80955fdc

		Model: {'id': '0c9a88010e514b75a768aa6d80955fdc', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.007, 'Rank IC': 0.044, 'Rank ICIR': 0.228}, 'data_train_vec': ['2023-04-01', '2025-06-30'], 'train_time_vec': ['2026-04-01', '2026-04-01'], 'rank_icir': '0.228', 'weight': '0.070'}

	Recorder: 2d85f8c4be864ec6bcbbb3ba18d08b42

		Model: {'id': '2d85f8c4be864ec6bcbbb3ba18d08b42', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.142, 'Rank IC': 0.03, 'Rank ICIR': 0.256}, 'data_train_vec': ['2024-04-01', '2025-09-30'], 'train_time_vec': ['2026-04-01', '2026-04-01'], 'rank_icir': '0.256', 'weight': '0.078'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260401_14 211030464154893575 (Recorders: 3/5)

	Recorder: 7227654f293d4789bce5d884de2830d7

		Model: {'id': '7227654f293d4789bce5d884de2830d7', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.12, 'Rank IC': 0.04, 'Rank ICIR': 0.222}, 'data_train_vec': ['2021-04-01', '2024-12-31'], 'train_time_vec': ['2026-04-01', '2026-04-01'], 'rank_icir': '0.222', 'weight': '0.068'}

	Recorder: 209d9afeabbc4143bde4b7319edfc43c

		Model: {'id': '209d9afeabbc4143bde4b7319edfc43c', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.088, 'Rank IC': 0.05, 'Rank ICIR': 0.285}, 'data_train_vec': ['2023-04-01', '2025-06-30'], 'train_time_vec': ['2026-04-01', '2026-04-01'], 'rank_icir': '0.285', 'weight': '0.087'}

	Recorder: ebeab9846ec34aa3ba761825fea5a21c

		Model: {'id': 'ebeab9846ec34aa3ba761825fea5a21c', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.271, 'Rank IC': 0.035, 'Rank ICIR': 0.349}, 'data_train_vec': ['2024-04-01', '2025-09-30'], 'train_time_vec': ['2026-04-01', '2026-04-01'], 'rank_icir': '0.349', 'weight': '0.107'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260401_14 301264928463356075 (Recorders: 4/5)

	Recorder: a60044bffb6447ffb698307cb77a3d0b

		Model: {'id': 'a60044bffb6447ffb698307cb77a3d0b', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.101, 'Rank IC': 0.023, 'Rank ICIR': 0.185}, 'data_train_vec': ['2021-04-01', '2024-12-31'], 'train_time_vec': ['2026-04-01', '2026-04-01'], 'rank_icir': '0.185', 'weight': '0.057'}

	Recorder: 0cd4b7813ef64c78abc3ba50ecbbd66f

		Model: {'id': '0cd4b7813ef64c78abc3ba50ecbbd66f', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.024, 'Rank IC': 0.02, 'Rank ICIR': 0.172}, 'data_train_vec': ['2022-04-01', '2025-03-31'], 'train_time_vec': ['2026-04-01', '2026-04-01'], 'rank_icir': '0.172', 'weight': '0.053'}

	Recorder: 26a51e56e64a4837b93b1d8273c02d70

		Model: {'id': '26a51e56e64a4837b93b1d8273c02d70', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.116, 'Rank IC': 0.039, 'Rank ICIR': 0.325}, 'data_train_vec': ['2023-04-01', '2025-06-30'], 'train_time_vec': ['2026-04-01', '2026-04-01'], 'rank_icir': '0.325', 'weight': '0.099'}

	Recorder: c1f7d9e0f8524a35b20beeddb1f07604

		Model: {'id': 'c1f7d9e0f8524a35b20beeddb1f07604', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.054, 'Rank IC': 0.003, 'Rank ICIR': 0.025}, 'data_train_vec': ['2025-04-01', '2025-12-31'], 'train_time_vec': ['2026-04-01', '2026-04-01'], 'rank_icir': '0.025', 'weight': '0.008'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260401_14 612423604665597846 (Recorders: 2/5)

	Recorder: 8e2e52f4cd354383b413aaccb2869a6e

		Model: {'id': '8e2e52f4cd354383b413aaccb2869a6e', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.118, 'Rank IC': 0.034, 'Rank ICIR': 0.181}, 'data_train_vec': ['2021-04-01', '2024-12-31'], 'train_time_vec': ['2026-04-01', '2026-04-01'], 'rank_icir': '0.181', 'weight': '0.055'}

	Recorder: 6400d1769a7840649267a08c8e12d8cb

		Model: {'id': '6400d1769a7840649267a08c8e12d8cb', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.12, 'Rank IC': 0.014, 'Rank ICIR': 0.155}, 'data_train_vec': ['2025-04-01', '2025-12-31'], 'train_time_vec': ['2026-04-01', '2026-04-01'], 'rank_icir': '0.155', 'weight': '0.047'}
