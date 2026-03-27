# params 
 {'predict_dates': [{'start': '2026-03-27', 'end': '2026-03-27'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260327_16 320294645895328605 (Recorders: 5/5)

	Recorder: 2963ca91c66f463cb695c741656806e0

		Model: {'id': '2963ca91c66f463cb695c741656806e0', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.046, 'Rank IC': 0.021, 'Rank ICIR': 0.157}, 'data_train_vec': ['2021-03-27', '2024-12-26'], 'train_time_vec': ['2026-03-27', '2026-03-27'], 'rank_icir': '0.157', 'weight': '0.046'}

	Recorder: cb2973b895ee42b991ccf82acc570135

		Model: {'id': 'cb2973b895ee42b991ccf82acc570135', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.058, 'Rank IC': 0.034, 'Rank ICIR': 0.169}, 'data_train_vec': ['2022-03-27', '2025-03-26'], 'train_time_vec': ['2026-03-27', '2026-03-27'], 'rank_icir': '0.169', 'weight': '0.050'}

	Recorder: 1e665f7806514434912959a5443fcfae

		Model: {'id': '1e665f7806514434912959a5443fcfae', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.008, 'Rank IC': 0.049, 'Rank ICIR': 0.324}, 'data_train_vec': ['2023-03-27', '2025-06-26'], 'train_time_vec': ['2026-03-27', '2026-03-27'], 'rank_icir': '0.324', 'weight': '0.096'}

	Recorder: 8bda2dd99868480aa1c19d140cf215f5

		Model: {'id': '8bda2dd99868480aa1c19d140cf215f5', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.093, 'Rank IC': 0.036, 'Rank ICIR': 0.249}, 'data_train_vec': ['2024-03-27', '2025-09-26'], 'train_time_vec': ['2026-03-27', '2026-03-27'], 'rank_icir': '0.249', 'weight': '0.074'}

	Recorder: 824f4f7675c34fd2abf5e1ccf9f409e6

		Model: {'id': '824f4f7675c34fd2abf5e1ccf9f409e6', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.019, 'Rank IC': 0.005, 'Rank ICIR': 0.036}, 'data_train_vec': ['2025-03-27', '2025-12-26'], 'train_time_vec': ['2026-03-27', '2026-03-27'], 'rank_icir': '0.036', 'weight': '0.011'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260327_16 532017430369424405 (Recorders: 2/5)

	Recorder: 4da6c2d082c4452eadceb1712f5d9c24

		Model: {'id': '4da6c2d082c4452eadceb1712f5d9c24', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.045, 'Rank IC': 0.026, 'Rank ICIR': 0.162}, 'data_train_vec': ['2021-03-27', '2024-12-26'], 'train_time_vec': ['2026-03-27', '2026-03-27'], 'rank_icir': '0.162', 'weight': '0.048'}

	Recorder: 9f42ff1ed77e4ea59f28a44051c31a74

		Model: {'id': '9f42ff1ed77e4ea59f28a44051c31a74', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.285, 'Rank IC': 0.046, 'Rank ICIR': 0.36}, 'data_train_vec': ['2024-03-27', '2025-09-26'], 'train_time_vec': ['2026-03-27', '2026-03-27'], 'rank_icir': '0.360', 'weight': '0.106'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260327_13 650496620326202449 (Recorders: 3/5)

	Recorder: 0443ad34d1a9480e8fb3d77f45c1af07

		Model: {'id': '0443ad34d1a9480e8fb3d77f45c1af07', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.117, 'Rank IC': 0.037, 'Rank ICIR': 0.215}, 'data_train_vec': ['2021-03-27', '2024-12-26'], 'train_time_vec': ['2026-03-27', '2026-03-27'], 'rank_icir': '0.215', 'weight': '0.064'}

	Recorder: 7a01913d6ea3464ea8263e06d32d9a65

		Model: {'id': '7a01913d6ea3464ea8263e06d32d9a65', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.268, 'Rank IC': 0.037, 'Rank ICIR': 0.299}, 'data_train_vec': ['2024-03-27', '2025-09-26'], 'train_time_vec': ['2026-03-27', '2026-03-27'], 'rank_icir': '0.299', 'weight': '0.088'}

	Recorder: 02a4a993e291427fa158b062b8e1678d

		Model: {'id': '02a4a993e291427fa158b062b8e1678d', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.014, 'Rank IC': 0.015, 'Rank ICIR': 0.141}, 'data_train_vec': ['2025-03-27', '2025-12-26'], 'train_time_vec': ['2026-03-27', '2026-03-27'], 'rank_icir': '0.141', 'weight': '0.042'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260327_13 858830480174360569 (Recorders: 5/5)

	Recorder: 30b5324cc51c43069bb9f3fc2a8a81de

		Model: {'id': '30b5324cc51c43069bb9f3fc2a8a81de', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.166, 'Rank IC': 0.028, 'Rank ICIR': 0.24}, 'data_train_vec': ['2021-03-27', '2024-12-26'], 'train_time_vec': ['2026-03-27', '2026-03-27'], 'rank_icir': '0.240', 'weight': '0.071'}

	Recorder: e1cf2aab3edc42639dd191665067dbf3

		Model: {'id': 'e1cf2aab3edc42639dd191665067dbf3', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.057, 'Rank IC': 0.023, 'Rank ICIR': 0.199}, 'data_train_vec': ['2022-03-27', '2025-03-26'], 'train_time_vec': ['2026-03-27', '2026-03-27'], 'rank_icir': '0.199', 'weight': '0.059'}

	Recorder: f322cc6627fd408c95f2d55eb72025a5

		Model: {'id': 'f322cc6627fd408c95f2d55eb72025a5', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.136, 'Rank IC': 0.039, 'Rank ICIR': 0.353}, 'data_train_vec': ['2023-03-27', '2025-06-26'], 'train_time_vec': ['2026-03-27', '2026-03-27'], 'rank_icir': '0.353', 'weight': '0.104'}

	Recorder: 51240b41fad04ef2bf8964bd23e5c9b5

		Model: {'id': '51240b41fad04ef2bf8964bd23e5c9b5', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.127, 'Rank IC': 0.015, 'Rank ICIR': 0.121}, 'data_train_vec': ['2024-03-27', '2025-09-26'], 'train_time_vec': ['2026-03-27', '2026-03-27'], 'rank_icir': '0.121', 'weight': '0.036'}

	Recorder: c8793dee5a4142bcaed070c7b1236a29

		Model: {'id': 'c8793dee5a4142bcaed070c7b1236a29', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.075, 'Rank IC': 0.017, 'Rank ICIR': 0.151}, 'data_train_vec': ['2025-03-27', '2025-12-26'], 'train_time_vec': ['2026-03-27', '2026-03-27'], 'rank_icir': '0.151', 'weight': '0.045'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260327_13 123488293953560923 (Recorders: 1/5)

	Recorder: ab4c88c01ab04da287ce3ac244dd11e1

		Model: {'id': 'ab4c88c01ab04da287ce3ac244dd11e1', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.067, 'Rank IC': 0.037, 'Rank ICIR': 0.205}, 'data_train_vec': ['2021-03-27', '2024-12-26'], 'train_time_vec': ['2026-03-27', '2026-03-27'], 'rank_icir': '0.205', 'weight': '0.061'}
