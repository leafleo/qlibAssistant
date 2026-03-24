# params 
 {'predict_dates': [{'start': '2026-03-24', 'end': '2026-03-24'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260324_16 413163681144010824 (Recorders: 3/5)

	Recorder: af710c3c2a24488f9167558293ae3585

		Model: {'id': 'af710c3c2a24488f9167558293ae3585', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.035, 'Rank IC': 0.029, 'Rank ICIR': 0.172}, 'data_train_vec': ['2021-03-24', '2024-12-23'], 'train_time_vec': ['2026-03-24', '2026-03-24'], 'rank_icir': '0.172', 'weight': '0.039'}

	Recorder: a086411477fb4d22b092816900ed9b17

		Model: {'id': 'a086411477fb4d22b092816900ed9b17', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.101, 'Rank IC': 0.04, 'Rank ICIR': 0.296}, 'data_train_vec': ['2024-03-24', '2025-09-23'], 'train_time_vec': ['2026-03-24', '2026-03-24'], 'rank_icir': '0.296', 'weight': '0.067'}

	Recorder: 7ba3ae7a014e44ab9049e33ce34145c7

		Model: {'id': '7ba3ae7a014e44ab9049e33ce34145c7', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.018, 'Rank IC': 0.031, 'Rank ICIR': 0.255}, 'data_train_vec': ['2025-03-24', '2025-12-23'], 'train_time_vec': ['2026-03-24', '2026-03-24'], 'rank_icir': '0.255', 'weight': '0.057'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260324_16 451825126230781251 (Recorders: 2/5)

	Recorder: 902f75cbb7234c078472011019013a85

		Model: {'id': '902f75cbb7234c078472011019013a85', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.057, 'Rank IC': 0.024, 'Rank ICIR': 0.187}, 'data_train_vec': ['2021-03-24', '2024-12-23'], 'train_time_vec': ['2026-03-24', '2026-03-24'], 'rank_icir': '0.187', 'weight': '0.042'}

	Recorder: 7166a09c83644526b299ae85dc6e330c

		Model: {'id': '7166a09c83644526b299ae85dc6e330c', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.348, 'Rank IC': 0.045, 'Rank ICIR': 0.413}, 'data_train_vec': ['2024-03-24', '2025-09-23'], 'train_time_vec': ['2026-03-24', '2026-03-24'], 'rank_icir': '0.413', 'weight': '0.093'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260324_14 615180146917420703 (Recorders: 3/5)

	Recorder: facb3559fb4f461198aa7f9818dd0488

		Model: {'id': 'facb3559fb4f461198aa7f9818dd0488', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.125, 'Rank IC': 0.039, 'Rank ICIR': 0.229}, 'data_train_vec': ['2021-03-24', '2024-12-23'], 'train_time_vec': ['2026-03-24', '2026-03-24'], 'rank_icir': '0.229', 'weight': '0.052'}

	Recorder: 6d1051ba1370431594cd0bb84107d155

		Model: {'id': '6d1051ba1370431594cd0bb84107d155', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.037, 'ICIR': 0.349, 'Rank IC': 0.048, 'Rank ICIR': 0.41}, 'data_train_vec': ['2024-03-24', '2025-09-23'], 'train_time_vec': ['2026-03-24', '2026-03-24'], 'rank_icir': '0.410', 'weight': '0.092'}

	Recorder: 6ca04d6da2ad4a919d292bdf62257676

		Model: {'id': '6ca04d6da2ad4a919d292bdf62257676', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.085, 'Rank IC': 0.023, 'Rank ICIR': 0.237}, 'data_train_vec': ['2025-03-24', '2025-12-23'], 'train_time_vec': ['2026-03-24', '2026-03-24'], 'rank_icir': '0.237', 'weight': '0.053'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260324_13 732725215060389747 (Recorders: 5/5)

	Recorder: 1d16cc7db039405f854e79a689bd8b65

		Model: {'id': '1d16cc7db039405f854e79a689bd8b65', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.168, 'Rank IC': 0.027, 'Rank ICIR': 0.235}, 'data_train_vec': ['2021-03-24', '2024-12-23'], 'train_time_vec': ['2026-03-24', '2026-03-24'], 'rank_icir': '0.235', 'weight': '0.053'}

	Recorder: 0bf6402318624622a56126ddf19fd7d3

		Model: {'id': '0bf6402318624622a56126ddf19fd7d3', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.054, 'Rank IC': 0.02, 'Rank ICIR': 0.178}, 'data_train_vec': ['2022-03-24', '2025-03-23'], 'train_time_vec': ['2026-03-24', '2026-03-24'], 'rank_icir': '0.178', 'weight': '0.040'}

	Recorder: 81ad02a7f7064c528529d1474e0aa362

		Model: {'id': '81ad02a7f7064c528529d1474e0aa362', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.125, 'Rank IC': 0.039, 'Rank ICIR': 0.361}, 'data_train_vec': ['2023-03-24', '2025-06-23'], 'train_time_vec': ['2026-03-24', '2026-03-24'], 'rank_icir': '0.361', 'weight': '0.081'}

	Recorder: 372488d433cd4a8e8d34b9887915f26c

		Model: {'id': '372488d433cd4a8e8d34b9887915f26c', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.141, 'Rank IC': 0.023, 'Rank ICIR': 0.181}, 'data_train_vec': ['2024-03-24', '2025-09-23'], 'train_time_vec': ['2026-03-24', '2026-03-24'], 'rank_icir': '0.181', 'weight': '0.041'}

	Recorder: 30940cee4fb349078879bdda429d6b80

		Model: {'id': '30940cee4fb349078879bdda429d6b80', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.275, 'Rank IC': 0.036, 'Rank ICIR': 0.357}, 'data_train_vec': ['2025-03-24', '2025-12-23'], 'train_time_vec': ['2026-03-24', '2026-03-24'], 'rank_icir': '0.357', 'weight': '0.080'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260324_13 942078502722367199 (Recorders: 3/5)

	Recorder: 24fab8fab01c4ffaba43ea4250b2580a

		Model: {'id': '24fab8fab01c4ffaba43ea4250b2580a', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.09, 'Rank IC': 0.036, 'Rank ICIR': 0.197}, 'data_train_vec': ['2021-03-24', '2024-12-23'], 'train_time_vec': ['2026-03-24', '2026-03-24'], 'rank_icir': '0.197', 'weight': '0.044'}

	Recorder: 0896ff8e55fb4746adf1f4b94e233ba9

		Model: {'id': '0896ff8e55fb4746adf1f4b94e233ba9', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.192, 'Rank IC': 0.041, 'Rank ICIR': 0.43}, 'data_train_vec': ['2024-03-24', '2025-09-23'], 'train_time_vec': ['2026-03-24', '2026-03-24'], 'rank_icir': '0.430', 'weight': '0.097'}

	Recorder: 3f406e8b78f2427098cbb22eb2624772

		Model: {'id': '3f406e8b78f2427098cbb22eb2624772', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.174, 'Rank IC': 0.026, 'Rank ICIR': 0.301}, 'data_train_vec': ['2025-03-24', '2025-12-23'], 'train_time_vec': ['2026-03-24', '2026-03-24'], 'rank_icir': '0.301', 'weight': '0.068'}
