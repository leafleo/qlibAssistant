# params 
 {'predict_dates': [{'start': '2026-03-30', 'end': '2026-03-30'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260330_16 790935859460018201 (Recorders: 3/5)

	Recorder: 6af2f6a3be2f42449960269a11e78784

		Model: {'id': '6af2f6a3be2f42449960269a11e78784', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.144, 'Rank IC': 0.044, 'Rank ICIR': 0.295}, 'data_train_vec': ['2021-03-30', '2024-12-29'], 'train_time_vec': ['2026-03-30', '2026-03-30'], 'rank_icir': '0.295', 'weight': '0.069'}

	Recorder: fab74cb360b0470f868a1fe893337942

		Model: {'id': 'fab74cb360b0470f868a1fe893337942', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.021, 'Rank IC': 0.04, 'Rank ICIR': 0.24}, 'data_train_vec': ['2023-03-30', '2025-06-29'], 'train_time_vec': ['2026-03-30', '2026-03-30'], 'rank_icir': '0.240', 'weight': '0.056'}

	Recorder: 699ad4d04db14d64b8d2984d2ebb8f0d

		Model: {'id': '699ad4d04db14d64b8d2984d2ebb8f0d', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.137, 'Rank IC': 0.055, 'Rank ICIR': 0.367}, 'data_train_vec': ['2024-03-30', '2025-09-29'], 'train_time_vec': ['2026-03-30', '2026-03-30'], 'rank_icir': '0.367', 'weight': '0.085'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260330_16 311915808592580288 (Recorders: 3/5)

	Recorder: 936781401e7c4c4d848477173008ecbd

		Model: {'id': '936781401e7c4c4d848477173008ecbd', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.024, 'Rank IC': 0.026, 'Rank ICIR': 0.163}, 'data_train_vec': ['2021-03-30', '2024-12-29'], 'train_time_vec': ['2026-03-30', '2026-03-30'], 'rank_icir': '0.163', 'weight': '0.038'}

	Recorder: b877a8cefd8b4fb2abf8626a076c8bd9

		Model: {'id': 'b877a8cefd8b4fb2abf8626a076c8bd9', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.019, 'Rank IC': 0.036, 'Rank ICIR': 0.221}, 'data_train_vec': ['2023-03-30', '2025-06-29'], 'train_time_vec': ['2026-03-30', '2026-03-30'], 'rank_icir': '0.221', 'weight': '0.051'}

	Recorder: d03eba34dce8417a81a316a406afdfb3

		Model: {'id': 'd03eba34dce8417a81a316a406afdfb3', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.312, 'Rank IC': 0.048, 'Rank ICIR': 0.366}, 'data_train_vec': ['2024-03-30', '2025-09-29'], 'train_time_vec': ['2026-03-30', '2026-03-30'], 'rank_icir': '0.366', 'weight': '0.085'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260330_14 804613700014397450 (Recorders: 4/5)

	Recorder: 561a00e2a2b04f22bb7134a714377b19

		Model: {'id': '561a00e2a2b04f22bb7134a714377b19', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.109, 'Rank IC': 0.036, 'Rank ICIR': 0.213}, 'data_train_vec': ['2021-03-30', '2024-12-29'], 'train_time_vec': ['2026-03-30', '2026-03-30'], 'rank_icir': '0.213', 'weight': '0.050'}

	Recorder: 862f1a4fd6314c94aaba58645034acf0

		Model: {'id': '862f1a4fd6314c94aaba58645034acf0', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.009, 'Rank IC': 0.037, 'Rank ICIR': 0.218}, 'data_train_vec': ['2023-03-30', '2025-06-29'], 'train_time_vec': ['2026-03-30', '2026-03-30'], 'rank_icir': '0.218', 'weight': '0.051'}

	Recorder: 3f4132e28d124a98ae2e88984134901a

		Model: {'id': '3f4132e28d124a98ae2e88984134901a', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.306, 'Rank IC': 0.04, 'Rank ICIR': 0.361}, 'data_train_vec': ['2024-03-30', '2025-09-29'], 'train_time_vec': ['2026-03-30', '2026-03-30'], 'rank_icir': '0.361', 'weight': '0.084'}

	Recorder: 080d264b77c54f73817f20d21a362337

		Model: {'id': '080d264b77c54f73817f20d21a362337', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.078, 'Rank IC': 0.02, 'Rank ICIR': 0.203}, 'data_train_vec': ['2025-03-28', '2025-12-27'], 'train_time_vec': ['2026-03-30', '2026-03-30'], 'rank_icir': '0.203', 'weight': '0.047'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260330_14 902396784744645668 (Recorders: 5/5)

	Recorder: 8aed9429296e4f00a0f1dbb9a917a6fc

		Model: {'id': '8aed9429296e4f00a0f1dbb9a917a6fc', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.139, 'Rank IC': 0.027, 'Rank ICIR': 0.228}, 'data_train_vec': ['2021-03-30', '2024-12-29'], 'train_time_vec': ['2026-03-30', '2026-03-30'], 'rank_icir': '0.228', 'weight': '0.053'}

	Recorder: 04b77bf227bd46d4b0a63af6d5093958

		Model: {'id': '04b77bf227bd46d4b0a63af6d5093958', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.024, 'Rank IC': 0.019, 'Rank ICIR': 0.168}, 'data_train_vec': ['2022-03-30', '2025-03-29'], 'train_time_vec': ['2026-03-30', '2026-03-30'], 'rank_icir': '0.168', 'weight': '0.039'}

	Recorder: 286bb6684e264567809e42018430d390

		Model: {'id': '286bb6684e264567809e42018430d390', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.118, 'Rank IC': 0.037, 'Rank ICIR': 0.334}, 'data_train_vec': ['2023-03-30', '2025-06-29'], 'train_time_vec': ['2026-03-30', '2026-03-30'], 'rank_icir': '0.334', 'weight': '0.078'}

	Recorder: 7189fc439c9846c3b789e0dd6e1f6879

		Model: {'id': '7189fc439c9846c3b789e0dd6e1f6879', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.08, 'Rank IC': 0.012, 'Rank ICIR': 0.095}, 'data_train_vec': ['2024-03-30', '2025-09-29'], 'train_time_vec': ['2026-03-30', '2026-03-30'], 'rank_icir': '0.095', 'weight': '0.022'}

	Recorder: 58854abeb35e413ebf482bb3f0feac38

		Model: {'id': '58854abeb35e413ebf482bb3f0feac38', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.134, 'Rank IC': 0.022, 'Rank ICIR': 0.194}, 'data_train_vec': ['2025-03-28', '2025-12-27'], 'train_time_vec': ['2026-03-30', '2026-03-30'], 'rank_icir': '0.194', 'weight': '0.045'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260330_13 953321548925988442 (Recorders: 3/5)

	Recorder: 34df6160b100422d83623f61f3ddfe28

		Model: {'id': '34df6160b100422d83623f61f3ddfe28', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.063, 'Rank IC': 0.038, 'Rank ICIR': 0.216}, 'data_train_vec': ['2021-03-30', '2024-12-29'], 'train_time_vec': ['2026-03-30', '2026-03-30'], 'rank_icir': '0.216', 'weight': '0.050'}

	Recorder: a96ab925d92f43f3b2ee43dab0460d6e

		Model: {'id': 'a96ab925d92f43f3b2ee43dab0460d6e', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.019, 'Rank IC': 0.033, 'Rank ICIR': 0.199}, 'data_train_vec': ['2023-03-30', '2025-06-29'], 'train_time_vec': ['2026-03-30', '2026-03-30'], 'rank_icir': '0.199', 'weight': '0.046'}

	Recorder: 723d71ab70144cfcadcc841232df0d13

		Model: {'id': '723d71ab70144cfcadcc841232df0d13', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.071, 'Rank IC': 0.024, 'Rank ICIR': 0.22}, 'data_train_vec': ['2024-03-30', '2025-09-29'], 'train_time_vec': ['2026-03-30', '2026-03-30'], 'rank_icir': '0.220', 'weight': '0.051'}
