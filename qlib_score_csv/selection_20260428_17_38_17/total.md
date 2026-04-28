# params 
 {'predict_dates': [{'start': '2026-04-28', 'end': '2026-04-28'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260428_17 208010147168129291 (Recorders: 3/5)

	Recorder: 07f1c09778d7405da857ecc1d9616dd8

		Model: {'id': '07f1c09778d7405da857ecc1d9616dd8', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.075, 'Rank IC': 0.027, 'Rank ICIR': 0.191}, 'data_train_vec': ['2023-04-28', '2025-07-27'], 'train_time_vec': ['2026-04-28', '2026-04-28'], 'rank_icir': '0.191', 'weight': '0.070'}

	Recorder: 8efb863394454b61bf5ee5e015a6370f

		Model: {'id': '8efb863394454b61bf5ee5e015a6370f', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.082, 'Rank IC': 0.017, 'Rank ICIR': 0.169}, 'data_train_vec': ['2024-04-28', '2025-10-27'], 'train_time_vec': ['2026-04-28', '2026-04-28'], 'rank_icir': '0.169', 'weight': '0.062'}

	Recorder: e6f727f33c274651b1bba3e06caeafce

		Model: {'id': 'e6f727f33c274651b1bba3e06caeafce', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.288, 'Rank IC': 0.036, 'Rank ICIR': 0.269}, 'data_train_vec': ['2025-04-28', '2026-01-27'], 'train_time_vec': ['2026-04-28', '2026-04-28'], 'rank_icir': '0.269', 'weight': '0.099'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260428_17 656763044907242915 (Recorders: 3/5)

	Recorder: 70d0b56629e5476b8990d288ec22ae06

		Model: {'id': '70d0b56629e5476b8990d288ec22ae06', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.085, 'Rank IC': 0.032, 'Rank ICIR': 0.208}, 'data_train_vec': ['2023-04-28', '2025-07-27'], 'train_time_vec': ['2026-04-28', '2026-04-28'], 'rank_icir': '0.208', 'weight': '0.076'}

	Recorder: 6aca6da476054344af49e1001e5f62fc

		Model: {'id': '6aca6da476054344af49e1001e5f62fc', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.086, 'Rank IC': 0.013, 'Rank ICIR': 0.118}, 'data_train_vec': ['2024-04-28', '2025-10-27'], 'train_time_vec': ['2026-04-28', '2026-04-28'], 'rank_icir': '0.118', 'weight': '0.043'}

	Recorder: 7f262d80be494535b641586e0020fd77

		Model: {'id': '7f262d80be494535b641586e0020fd77', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.056, 'ICIR': 0.424, 'Rank IC': 0.03, 'Rank ICIR': 0.214}, 'data_train_vec': ['2025-04-28', '2026-01-27'], 'train_time_vec': ['2026-04-28', '2026-04-28'], 'rank_icir': '0.214', 'weight': '0.079'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260428_14 442162771586127165 (Recorders: 3/5)

	Recorder: fcc9f11eb196404b8996b1daa3cf3657

		Model: {'id': 'fcc9f11eb196404b8996b1daa3cf3657', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.076, 'Rank IC': 0.042, 'Rank ICIR': 0.257}, 'data_train_vec': ['2023-04-28', '2025-07-27'], 'train_time_vec': ['2026-04-28', '2026-04-28'], 'rank_icir': '0.257', 'weight': '0.094'}

	Recorder: a01955a00da449aead56e1e00d68e10a

		Model: {'id': 'a01955a00da449aead56e1e00d68e10a', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.061, 'Rank IC': 0.006, 'Rank ICIR': 0.053}, 'data_train_vec': ['2024-04-28', '2025-10-27'], 'train_time_vec': ['2026-04-28', '2026-04-28'], 'rank_icir': '0.053', 'weight': '0.019'}

	Recorder: 266409b2197c4bf8b527701545991e27

		Model: {'id': '266409b2197c4bf8b527701545991e27', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.204, 'Rank IC': 0.012, 'Rank ICIR': 0.065}, 'data_train_vec': ['2025-04-28', '2026-01-27'], 'train_time_vec': ['2026-04-28', '2026-04-28'], 'rank_icir': '0.065', 'weight': '0.024'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260428_14 855833537949804090 (Recorders: 3/5)

	Recorder: 78aee22c6dc742b8ae21a3c39c4cbe25

		Model: {'id': '78aee22c6dc742b8ae21a3c39c4cbe25', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.03, 'Rank IC': 0.029, 'Rank ICIR': 0.246}, 'data_train_vec': ['2023-04-28', '2025-07-27'], 'train_time_vec': ['2026-04-28', '2026-04-28'], 'rank_icir': '0.246', 'weight': '0.090'}

	Recorder: 26d72a6fd85646cba900a3804ce59c3c

		Model: {'id': '26d72a6fd85646cba900a3804ce59c3c', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.013, 'Rank IC': 0.009, 'Rank ICIR': 0.075}, 'data_train_vec': ['2024-04-28', '2025-10-27'], 'train_time_vec': ['2026-04-28', '2026-04-28'], 'rank_icir': '0.075', 'weight': '0.028'}

	Recorder: 85810eafa8fc42b9ab559cf8c8528a6d

		Model: {'id': '85810eafa8fc42b9ab559cf8c8528a6d', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.066, 'ICIR': 0.579, 'Rank IC': 0.043, 'Rank ICIR': 0.328}, 'data_train_vec': ['2025-04-28', '2026-01-27'], 'train_time_vec': ['2026-04-28', '2026-04-28'], 'rank_icir': '0.328', 'weight': '0.120'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260428_14 869240769910700770 (Recorders: 3/5)

	Recorder: a38ea7fc39e84297abb0506ed9a0d990

		Model: {'id': 'a38ea7fc39e84297abb0506ed9a0d990', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.009, 'Rank IC': 0.018, 'Rank ICIR': 0.102}, 'data_train_vec': ['2021-04-28', '2025-01-27'], 'train_time_vec': ['2026-04-28', '2026-04-28'], 'rank_icir': '0.102', 'weight': '0.037'}

	Recorder: 45be5778d1004362998a7deaa09de76a

		Model: {'id': '45be5778d1004362998a7deaa09de76a', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.074, 'Rank IC': 0.037, 'Rank ICIR': 0.224}, 'data_train_vec': ['2023-04-28', '2025-07-27'], 'train_time_vec': ['2026-04-28', '2026-04-28'], 'rank_icir': '0.224', 'weight': '0.082'}

	Recorder: ffb8de82c5094678b53320ceba287aca

		Model: {'id': 'ffb8de82c5094678b53320ceba287aca', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.075, 'Rank IC': 0.024, 'Rank ICIR': 0.207}, 'data_train_vec': ['2024-04-28', '2025-10-27'], 'train_time_vec': ['2026-04-28', '2026-04-28'], 'rank_icir': '0.207', 'weight': '0.076'}
