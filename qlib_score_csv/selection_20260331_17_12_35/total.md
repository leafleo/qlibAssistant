# params 
 {'predict_dates': [{'start': '2026-03-31', 'end': '2026-03-31'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260331_16 393852060006209335 (Recorders: 3/5)

	Recorder: 504f50d3cdbf48afaebd71d7f89a675e

		Model: {'id': '504f50d3cdbf48afaebd71d7f89a675e', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.105, 'Rank IC': 0.026, 'Rank ICIR': 0.173}, 'data_train_vec': ['2021-03-31', '2024-12-30'], 'train_time_vec': ['2026-03-31', '2026-03-31'], 'rank_icir': '0.173', 'weight': '0.045'}

	Recorder: 8ffdbab107474a1e9cc395e41f773f5e

		Model: {'id': '8ffdbab107474a1e9cc395e41f773f5e', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.08, 'Rank IC': 0.048, 'Rank ICIR': 0.29}, 'data_train_vec': ['2023-03-30', '2025-06-29'], 'train_time_vec': ['2026-03-31', '2026-03-31'], 'rank_icir': '0.290', 'weight': '0.076'}

	Recorder: 6753da5be6884bf2ada0ec75fe046393

		Model: {'id': '6753da5be6884bf2ada0ec75fe046393', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.056, 'Rank IC': 0.053, 'Rank ICIR': 0.378}, 'data_train_vec': ['2024-03-30', '2025-09-29'], 'train_time_vec': ['2026-03-31', '2026-03-31'], 'rank_icir': '0.378', 'weight': '0.099'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260331_16 274986269529806283 (Recorders: 3/5)

	Recorder: d2228d671e6047998963114b95593592

		Model: {'id': 'd2228d671e6047998963114b95593592', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.011, 'Rank IC': 0.022, 'Rank ICIR': 0.141}, 'data_train_vec': ['2021-03-31', '2024-12-30'], 'train_time_vec': ['2026-03-31', '2026-03-31'], 'rank_icir': '0.141', 'weight': '0.037'}

	Recorder: a3276362553e416cb0b9735985378ddc

		Model: {'id': 'a3276362553e416cb0b9735985378ddc', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.062, 'Rank IC': 0.043, 'Rank ICIR': 0.27}, 'data_train_vec': ['2023-03-30', '2025-06-29'], 'train_time_vec': ['2026-03-31', '2026-03-31'], 'rank_icir': '0.270', 'weight': '0.070'}

	Recorder: 1913bc4355b04a16bfed172c5b0efa0d

		Model: {'id': '1913bc4355b04a16bfed172c5b0efa0d', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.303, 'Rank IC': 0.051, 'Rank ICIR': 0.383}, 'data_train_vec': ['2024-03-30', '2025-09-29'], 'train_time_vec': ['2026-03-31', '2026-03-31'], 'rank_icir': '0.383', 'weight': '0.100'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260331_14 309659402157592911 (Recorders: 3/5)

	Recorder: 8719b6a8bf484f0c85401efbc36af476

		Model: {'id': '8719b6a8bf484f0c85401efbc36af476', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.109, 'Rank IC': 0.038, 'Rank ICIR': 0.212}, 'data_train_vec': ['2021-03-31', '2024-12-30'], 'train_time_vec': ['2026-03-31', '2026-03-31'], 'rank_icir': '0.212', 'weight': '0.055'}

	Recorder: 86e01b0ffedb45b5922439413143f852

		Model: {'id': '86e01b0ffedb45b5922439413143f852', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.085, 'Rank IC': 0.048, 'Rank ICIR': 0.281}, 'data_train_vec': ['2023-03-30', '2025-06-29'], 'train_time_vec': ['2026-03-31', '2026-03-31'], 'rank_icir': '0.281', 'weight': '0.073'}

	Recorder: eae03f3c3a8142da94b7b90f2d1c074f

		Model: {'id': 'eae03f3c3a8142da94b7b90f2d1c074f', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.313, 'Rank IC': 0.041, 'Rank ICIR': 0.366}, 'data_train_vec': ['2024-03-30', '2025-09-29'], 'train_time_vec': ['2026-03-31', '2026-03-31'], 'rank_icir': '0.366', 'weight': '0.095'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260331_14 936895932730638578 (Recorders: 4/5)

	Recorder: b0820685eaa046418e39e56a023b79cd

		Model: {'id': 'b0820685eaa046418e39e56a023b79cd', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.143, 'Rank IC': 0.027, 'Rank ICIR': 0.229}, 'data_train_vec': ['2021-03-31', '2024-12-30'], 'train_time_vec': ['2026-03-31', '2026-03-31'], 'rank_icir': '0.229', 'weight': '0.060'}

	Recorder: a22c2c6563cc4dceb5ca76a55610cd3c

		Model: {'id': 'a22c2c6563cc4dceb5ca76a55610cd3c', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.037, 'Rank IC': 0.021, 'Rank ICIR': 0.184}, 'data_train_vec': ['2022-03-30', '2025-03-29'], 'train_time_vec': ['2026-03-31', '2026-03-31'], 'rank_icir': '0.184', 'weight': '0.048'}

	Recorder: 0428246af3004311b1a3e623d2dec380

		Model: {'id': '0428246af3004311b1a3e623d2dec380', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.156, 'Rank IC': 0.042, 'Rank ICIR': 0.388}, 'data_train_vec': ['2023-03-30', '2025-06-29'], 'train_time_vec': ['2026-03-31', '2026-03-31'], 'rank_icir': '0.388', 'weight': '0.101'}

	Recorder: 0d40c481a2654a94acef42f2a2fff06b

		Model: {'id': '0d40c481a2654a94acef42f2a2fff06b', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.043, 'Rank IC': 0.009, 'Rank ICIR': 0.072}, 'data_train_vec': ['2025-03-28', '2025-12-27'], 'train_time_vec': ['2026-03-31', '2026-03-31'], 'rank_icir': '0.072', 'weight': '0.019'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260331_13 371694385580305365 (Recorders: 2/5)

	Recorder: d05f5b8cceb94581b664bd8ffa591569

		Model: {'id': 'd05f5b8cceb94581b664bd8ffa591569', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.077, 'Rank IC': 0.038, 'Rank ICIR': 0.205}, 'data_train_vec': ['2021-03-31', '2024-12-30'], 'train_time_vec': ['2026-03-31', '2026-03-31'], 'rank_icir': '0.205', 'weight': '0.053'}

	Recorder: 1b2bf1eb25114f31abc629ee5e2a3359

		Model: {'id': '1b2bf1eb25114f31abc629ee5e2a3359', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.077, 'Rank IC': 0.043, 'Rank ICIR': 0.263}, 'data_train_vec': ['2023-03-30', '2025-06-29'], 'train_time_vec': ['2026-03-31', '2026-03-31'], 'rank_icir': '0.263', 'weight': '0.069'}
