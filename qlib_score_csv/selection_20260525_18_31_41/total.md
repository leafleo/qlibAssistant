# params 
 {'predict_dates': [{'start': '2026-05-25', 'end': '2026-05-25'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260525_18 390009943294810705 (Recorders: 3/5)

	Recorder: 02089fda4cde4e838352bcd8869c0bbe

		Model: {'id': '02089fda4cde4e838352bcd8869c0bbe', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.076, 'Rank IC': 0.031, 'Rank ICIR': 0.22}, 'data_train_vec': ['2021-05-25', '2025-02-24'], 'train_time_vec': ['2026-05-25', '2026-05-25'], 'rank_icir': '0.220', 'weight': '0.058'}

	Recorder: 4308f537c3f44671828750eddfcd391e

		Model: {'id': '4308f537c3f44671828750eddfcd391e', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.237, 'Rank IC': 0.034, 'Rank ICIR': 0.24}, 'data_train_vec': ['2023-05-25', '2025-08-24'], 'train_time_vec': ['2026-05-25', '2026-05-25'], 'rank_icir': '0.240', 'weight': '0.064'}

	Recorder: 874a7695eab74536814c9290336caddd

		Model: {'id': '874a7695eab74536814c9290336caddd', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.071, 'ICIR': 0.363, 'Rank IC': 0.05, 'Rank ICIR': 0.29}, 'data_train_vec': ['2025-05-25', '2026-02-24'], 'train_time_vec': ['2026-05-25', '2026-05-25'], 'rank_icir': '0.290', 'weight': '0.077'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260525_17 530050408904867925 (Recorders: 3/5)

	Recorder: ec3fe8a024b840a7a3ef10e5420422ca

		Model: {'id': 'ec3fe8a024b840a7a3ef10e5420422ca', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.082, 'Rank IC': 0.022, 'Rank ICIR': 0.17}, 'data_train_vec': ['2023-05-25', '2025-08-24'], 'train_time_vec': ['2026-05-25', '2026-05-25'], 'rank_icir': '0.170', 'weight': '0.045'}

	Recorder: 3cdffef28cba47f9a614d46e2ea9f54a

		Model: {'id': '3cdffef28cba47f9a614d46e2ea9f54a', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.173, 'Rank IC': 0.005, 'Rank ICIR': 0.041}, 'data_train_vec': ['2024-05-25', '2025-11-24'], 'train_time_vec': ['2026-05-25', '2026-05-25'], 'rank_icir': '0.041', 'weight': '0.011'}

	Recorder: 8b03081675eb4a11886176ad363a7f38

		Model: {'id': '8b03081675eb4a11886176ad363a7f38', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.095, 'ICIR': 0.536, 'Rank IC': 0.052, 'Rank ICIR': 0.273}, 'data_train_vec': ['2025-05-25', '2026-02-24'], 'train_time_vec': ['2026-05-25', '2026-05-25'], 'rank_icir': '0.273', 'weight': '0.072'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260525_15 455374161797618820 (Recorders: 4/5)

	Recorder: 651214621e94452ea62fef52c57faeba

		Model: {'id': '651214621e94452ea62fef52c57faeba', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.058, 'Rank IC': 0.032, 'Rank ICIR': 0.218}, 'data_train_vec': ['2021-05-25', '2025-02-24'], 'train_time_vec': ['2026-05-25', '2026-05-25'], 'rank_icir': '0.218', 'weight': '0.058'}

	Recorder: e4bb2a3885114c06898d9fbd9d9c154a

		Model: {'id': 'e4bb2a3885114c06898d9fbd9d9c154a', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.024, 'Rank IC': 0.036, 'Rank ICIR': 0.198}, 'data_train_vec': ['2022-05-25', '2025-05-24'], 'train_time_vec': ['2026-05-25', '2026-05-25'], 'rank_icir': '0.198', 'weight': '0.053'}

	Recorder: 3ae65ff58f274d38bdf15ad763968a84

		Model: {'id': '3ae65ff58f274d38bdf15ad763968a84', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.172, 'Rank IC': 0.036, 'Rank ICIR': 0.25}, 'data_train_vec': ['2023-05-25', '2025-08-24'], 'train_time_vec': ['2026-05-25', '2026-05-25'], 'rank_icir': '0.250', 'weight': '0.066'}

	Recorder: 365305ddccab4dd98caceea45e43960a

		Model: {'id': '365305ddccab4dd98caceea45e43960a', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.066, 'ICIR': 0.351, 'Rank IC': 0.041, 'Rank ICIR': 0.223}, 'data_train_vec': ['2025-05-25', '2026-02-24'], 'train_time_vec': ['2026-05-25', '2026-05-25'], 'rank_icir': '0.223', 'weight': '0.059'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260525_15 332192575501493651 (Recorders: 4/5)

	Recorder: a7e3883f52dd4344a1df7de6061aa888

		Model: {'id': 'a7e3883f52dd4344a1df7de6061aa888', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.063, 'Rank IC': 0.031, 'Rank ICIR': 0.277}, 'data_train_vec': ['2021-05-25', '2025-02-24'], 'train_time_vec': ['2026-05-25', '2026-05-25'], 'rank_icir': '0.277', 'weight': '0.074'}

	Recorder: 18fd3fe0528d4f2a8dd5eb65dbec08a8

		Model: {'id': '18fd3fe0528d4f2a8dd5eb65dbec08a8', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.094, 'Rank IC': 0.036, 'Rank ICIR': 0.329}, 'data_train_vec': ['2023-05-25', '2025-08-24'], 'train_time_vec': ['2026-05-25', '2026-05-25'], 'rank_icir': '0.329', 'weight': '0.087'}

	Recorder: e51d6b7ee8c24470a57211d7842c1378

		Model: {'id': 'e51d6b7ee8c24470a57211d7842c1378', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.015, 'Rank IC': 0.01, 'Rank ICIR': 0.079}, 'data_train_vec': ['2024-05-25', '2025-11-24'], 'train_time_vec': ['2026-05-25', '2026-05-25'], 'rank_icir': '0.079', 'weight': '0.021'}

	Recorder: 671e282f8b41416ab8a9e7985602f66e

		Model: {'id': '671e282f8b41416ab8a9e7985602f66e', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.11, 'ICIR': 0.624, 'Rank IC': 0.089, 'Rank ICIR': 0.45}, 'data_train_vec': ['2025-05-25', '2026-02-24'], 'train_time_vec': ['2026-05-25', '2026-05-25'], 'rank_icir': '0.450', 'weight': '0.119'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260525_15 453162236609771893 (Recorders: 2/5)

	Recorder: faea0b44b6e645a68f948067aea3d07b

		Model: {'id': 'faea0b44b6e645a68f948067aea3d07b', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.13, 'Rank IC': 0.034, 'Rank ICIR': 0.215}, 'data_train_vec': ['2023-05-25', '2025-08-24'], 'train_time_vec': ['2026-05-25', '2026-05-25'], 'rank_icir': '0.215', 'weight': '0.057'}

	Recorder: 40de00fc87f54eea914d549ef7f0c3d3

		Model: {'id': '40de00fc87f54eea914d549ef7f0c3d3', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.059, 'ICIR': 0.32, 'Rank IC': 0.042, 'Rank ICIR': 0.295}, 'data_train_vec': ['2025-05-25', '2026-02-24'], 'train_time_vec': ['2026-05-25', '2026-05-25'], 'rank_icir': '0.295', 'weight': '0.078'}
