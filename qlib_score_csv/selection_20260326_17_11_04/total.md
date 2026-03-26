# params 
 {'predict_dates': [{'start': '2026-03-26', 'end': '2026-03-26'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260326_16 126380044280906178 (Recorders: 3/5)

	Recorder: 5c1cd4323d904398a0c9624bdbb23204

		Model: {'id': '5c1cd4323d904398a0c9624bdbb23204', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.124, 'Rank IC': 0.026, 'Rank ICIR': 0.215}, 'data_train_vec': ['2021-03-26', '2024-12-25'], 'train_time_vec': ['2026-03-26', '2026-03-26'], 'rank_icir': '0.215', 'weight': '0.045'}

	Recorder: 2ca5a4f1480c4f629030f28e83200751

		Model: {'id': '2ca5a4f1480c4f629030f28e83200751', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.213, 'Rank IC': 0.022, 'Rank ICIR': 0.183}, 'data_train_vec': ['2024-03-26', '2025-09-25'], 'train_time_vec': ['2026-03-26', '2026-03-26'], 'rank_icir': '0.183', 'weight': '0.039'}

	Recorder: c5763c30e106439aa08af4c8215cc949

		Model: {'id': 'c5763c30e106439aa08af4c8215cc949', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.215, 'Rank IC': 0.045, 'Rank ICIR': 0.352}, 'data_train_vec': ['2025-03-26', '2025-12-25'], 'train_time_vec': ['2026-03-26', '2026-03-26'], 'rank_icir': '0.352', 'weight': '0.074'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260326_16 470608938617272110 (Recorders: 2/5)

	Recorder: e2fc3b7d8feb4887a1a481af112ea93e

		Model: {'id': 'e2fc3b7d8feb4887a1a481af112ea93e', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.059, 'Rank IC': 0.029, 'Rank ICIR': 0.196}, 'data_train_vec': ['2021-03-26', '2024-12-25'], 'train_time_vec': ['2026-03-26', '2026-03-26'], 'rank_icir': '0.196', 'weight': '0.041'}

	Recorder: 33d79a0d02d34c11a700cd6d931b64a7

		Model: {'id': '33d79a0d02d34c11a700cd6d931b64a7', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.036, 'ICIR': 0.391, 'Rank IC': 0.057, 'Rank ICIR': 0.482}, 'data_train_vec': ['2024-03-26', '2025-09-25'], 'train_time_vec': ['2026-03-26', '2026-03-26'], 'rank_icir': '0.482', 'weight': '0.102'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260326_14 272014003031697494 (Recorders: 4/5)

	Recorder: ca61f04f6d7841b486c9867e3d98faa8

		Model: {'id': 'ca61f04f6d7841b486c9867e3d98faa8', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.121, 'Rank IC': 0.038, 'Rank ICIR': 0.222}, 'data_train_vec': ['2021-03-26', '2024-12-25'], 'train_time_vec': ['2026-03-26', '2026-03-26'], 'rank_icir': '0.222', 'weight': '0.047'}

	Recorder: 5486fed40a1d44beb756936f1644a3a4

		Model: {'id': '5486fed40a1d44beb756936f1644a3a4', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.01, 'Rank IC': 0.038, 'Rank ICIR': 0.22}, 'data_train_vec': ['2023-03-26', '2025-06-25'], 'train_time_vec': ['2026-03-26', '2026-03-26'], 'rank_icir': '0.220', 'weight': '0.046'}

	Recorder: 62d9c39daac94f58a17d06810790dc53

		Model: {'id': '62d9c39daac94f58a17d06810790dc53', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.036, 'ICIR': 0.317, 'Rank IC': 0.042, 'Rank ICIR': 0.341}, 'data_train_vec': ['2024-03-26', '2025-09-25'], 'train_time_vec': ['2026-03-26', '2026-03-26'], 'rank_icir': '0.341', 'weight': '0.072'}

	Recorder: d19073ce203743f6956ff32b9e9a6231

		Model: {'id': 'd19073ce203743f6956ff32b9e9a6231', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.107, 'Rank IC': 0.026, 'Rank ICIR': 0.222}, 'data_train_vec': ['2025-03-26', '2025-12-25'], 'train_time_vec': ['2026-03-26', '2026-03-26'], 'rank_icir': '0.222', 'weight': '0.047'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260326_14 488260979985100003 (Recorders: 5/5)

	Recorder: db889391cf59461f90ede0f54326b075

		Model: {'id': 'db889391cf59461f90ede0f54326b075', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.183, 'Rank IC': 0.029, 'Rank ICIR': 0.251}, 'data_train_vec': ['2021-03-26', '2024-12-25'], 'train_time_vec': ['2026-03-26', '2026-03-26'], 'rank_icir': '0.251', 'weight': '0.053'}

	Recorder: 0472ae801704420ab6e040450436a7c7

		Model: {'id': '0472ae801704420ab6e040450436a7c7', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.047, 'Rank IC': 0.021, 'Rank ICIR': 0.181}, 'data_train_vec': ['2022-03-26', '2025-03-25'], 'train_time_vec': ['2026-03-26', '2026-03-26'], 'rank_icir': '0.181', 'weight': '0.038'}

	Recorder: d2097fea6c544f10b852f2c6e7d3f353

		Model: {'id': 'd2097fea6c544f10b852f2c6e7d3f353', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.149, 'Rank IC': 0.04, 'Rank ICIR': 0.362}, 'data_train_vec': ['2023-03-26', '2025-06-25'], 'train_time_vec': ['2026-03-26', '2026-03-26'], 'rank_icir': '0.362', 'weight': '0.076'}

	Recorder: e3ec9a312b4540468cada1864098ce3c

		Model: {'id': 'e3ec9a312b4540468cada1864098ce3c', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.118, 'Rank IC': 0.022, 'Rank ICIR': 0.174}, 'data_train_vec': ['2024-03-26', '2025-09-25'], 'train_time_vec': ['2026-03-26', '2026-03-26'], 'rank_icir': '0.174', 'weight': '0.037'}

	Recorder: 0fb7ae53b3854ca5b0b19be050404a4f

		Model: {'id': '0fb7ae53b3854ca5b0b19be050404a4f', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.151, 'Rank IC': 0.026, 'Rank ICIR': 0.246}, 'data_train_vec': ['2025-03-26', '2025-12-25'], 'train_time_vec': ['2026-03-26', '2026-03-26'], 'rank_icir': '0.246', 'weight': '0.052'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260326_13 786901423494076377 (Recorders: 3/5)

	Recorder: af840595959f49fca27b803e4f1184b3

		Model: {'id': 'af840595959f49fca27b803e4f1184b3', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.043, 'Rank IC': 0.03, 'Rank ICIR': 0.159}, 'data_train_vec': ['2021-03-26', '2024-12-25'], 'train_time_vec': ['2026-03-26', '2026-03-26'], 'rank_icir': '0.159', 'weight': '0.034'}

	Recorder: 5f81a77a85ad49629818defbfc8313f3

		Model: {'id': '5f81a77a85ad49629818defbfc8313f3', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.015, 'Rank IC': 0.051, 'Rank ICIR': 0.424}, 'data_train_vec': ['2024-03-26', '2025-09-25'], 'train_time_vec': ['2026-03-26', '2026-03-26'], 'rank_icir': '0.424', 'weight': '0.089'}

	Recorder: cbef2f904d6741f385037d8098bfaae5

		Model: {'id': 'cbef2f904d6741f385037d8098bfaae5', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.257, 'Rank IC': 0.046, 'Rank ICIR': 0.514}, 'data_train_vec': ['2025-03-26', '2025-12-25'], 'train_time_vec': ['2026-03-26', '2026-03-26'], 'rank_icir': '0.514', 'weight': '0.108'}
