# params 
 {'predict_dates': [{'start': '2026-04-16', 'end': '2026-04-16'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260416_16 775726081826953850 (Recorders: 3/5)

	Recorder: 3108e1fc825d467cb39a9c092cec4054

		Model: {'id': '3108e1fc825d467cb39a9c092cec4054', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.259, 'Rank IC': 0.045, 'Rank ICIR': 0.305}, 'data_train_vec': ['2023-04-16', '2025-07-15'], 'train_time_vec': ['2026-04-16', '2026-04-16'], 'rank_icir': '0.305', 'weight': '0.086'}

	Recorder: ba4389bd14f14353aa2df988a50bf5c3

		Model: {'id': 'ba4389bd14f14353aa2df988a50bf5c3', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.33, 'Rank IC': 0.056, 'Rank ICIR': 0.391}, 'data_train_vec': ['2024-04-16', '2025-10-15'], 'train_time_vec': ['2026-04-16', '2026-04-16'], 'rank_icir': '0.391', 'weight': '0.110'}

	Recorder: 94c2ff07cad5446aace8a888debc21ef

		Model: {'id': '94c2ff07cad5446aace8a888debc21ef', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.062, 'ICIR': 0.37, 'Rank IC': 0.048, 'Rank ICIR': 0.292}, 'data_train_vec': ['2025-04-16', '2026-01-15'], 'train_time_vec': ['2026-04-16', '2026-04-16'], 'rank_icir': '0.292', 'weight': '0.082'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260416_16 519006938358359654 (Recorders: 2/5)

	Recorder: 11f9584d67ca44e3bfd6fcf8aa708e4d

		Model: {'id': '11f9584d67ca44e3bfd6fcf8aa708e4d', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.125, 'Rank IC': 0.029, 'Rank ICIR': 0.239}, 'data_train_vec': ['2024-04-16', '2025-10-15'], 'train_time_vec': ['2026-04-16', '2026-04-16'], 'rank_icir': '0.239', 'weight': '0.067'}

	Recorder: 4962fcf45ecc472d8e497cbdd508151c

		Model: {'id': '4962fcf45ecc472d8e497cbdd508151c', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.041, 'ICIR': 0.305, 'Rank IC': 0.037, 'Rank ICIR': 0.245}, 'data_train_vec': ['2025-04-16', '2026-01-15'], 'train_time_vec': ['2026-04-16', '2026-04-16'], 'rank_icir': '0.245', 'weight': '0.069'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260416_14 521131414778389028 (Recorders: 4/5)

	Recorder: aa9749cab3e14ba787e4185a3d82daab

		Model: {'id': 'aa9749cab3e14ba787e4185a3d82daab', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.013, 'Rank IC': 0.021, 'Rank ICIR': 0.123}, 'data_train_vec': ['2021-04-16', '2025-01-15'], 'train_time_vec': ['2026-04-16', '2026-04-16'], 'rank_icir': '0.123', 'weight': '0.035'}

	Recorder: 13d71e4d75e044ee994b2d66b7dc870e

		Model: {'id': '13d71e4d75e044ee994b2d66b7dc870e', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.076, 'Rank IC': 0.044, 'Rank ICIR': 0.258}, 'data_train_vec': ['2023-04-16', '2025-07-15'], 'train_time_vec': ['2026-04-16', '2026-04-16'], 'rank_icir': '0.258', 'weight': '0.073'}

	Recorder: c6bf602572b2453382a629cad060a185

		Model: {'id': 'c6bf602572b2453382a629cad060a185', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.134, 'Rank IC': 0.021, 'Rank ICIR': 0.157}, 'data_train_vec': ['2024-04-16', '2025-10-15'], 'train_time_vec': ['2026-04-16', '2026-04-16'], 'rank_icir': '0.157', 'weight': '0.044'}

	Recorder: 0abf9f28b35c4c91a19236bfa1ef92ee

		Model: {'id': '0abf9f28b35c4c91a19236bfa1ef92ee', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.04, 'ICIR': 0.237, 'Rank IC': 0.026, 'Rank ICIR': 0.143}, 'data_train_vec': ['2025-04-16', '2026-01-15'], 'train_time_vec': ['2026-04-16', '2026-04-16'], 'rank_icir': '0.143', 'weight': '0.040'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260416_14 250402535299477381 (Recorders: 4/5)

	Recorder: 574ad5a933844a82a4790300841a6655

		Model: {'id': '574ad5a933844a82a4790300841a6655', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.032, 'Rank IC': 0.016, 'Rank ICIR': 0.136}, 'data_train_vec': ['2021-04-16', '2025-01-15'], 'train_time_vec': ['2026-04-16', '2026-04-16'], 'rank_icir': '0.136', 'weight': '0.038'}

	Recorder: caf375b47d084d47808789fec5087c2c

		Model: {'id': 'caf375b47d084d47808789fec5087c2c', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.033, 'Rank IC': 0.029, 'Rank ICIR': 0.242}, 'data_train_vec': ['2023-04-16', '2025-07-15'], 'train_time_vec': ['2026-04-16', '2026-04-16'], 'rank_icir': '0.242', 'weight': '0.068'}

	Recorder: a8ff1f18957d47b298fb7caa47760f3c

		Model: {'id': 'a8ff1f18957d47b298fb7caa47760f3c', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.076, 'Rank IC': 0.017, 'Rank ICIR': 0.142}, 'data_train_vec': ['2024-04-16', '2025-10-15'], 'train_time_vec': ['2026-04-16', '2026-04-16'], 'rank_icir': '0.142', 'weight': '0.040'}

	Recorder: 5daa3d8966b4476686f411e9b633788b

		Model: {'id': '5daa3d8966b4476686f411e9b633788b', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.062, 'ICIR': 0.364, 'Rank IC': 0.048, 'Rank ICIR': 0.269}, 'data_train_vec': ['2025-04-16', '2026-01-15'], 'train_time_vec': ['2026-04-16', '2026-04-16'], 'rank_icir': '0.269', 'weight': '0.076'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260416_14 303514979633231317 (Recorders: 3/5)

	Recorder: b5d28adc77224c41a1d546a230061062

		Model: {'id': 'b5d28adc77224c41a1d546a230061062', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.094, 'Rank IC': 0.021, 'Rank ICIR': 0.116}, 'data_train_vec': ['2021-04-16', '2025-01-15'], 'train_time_vec': ['2026-04-16', '2026-04-16'], 'rank_icir': '0.116', 'weight': '0.033'}

	Recorder: 39f4f609cd72403a9a32f52ec0c5f8b7

		Model: {'id': '39f4f609cd72403a9a32f52ec0c5f8b7', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.102, 'Rank IC': 0.04, 'Rank ICIR': 0.241}, 'data_train_vec': ['2023-04-16', '2025-07-15'], 'train_time_vec': ['2026-04-16', '2026-04-16'], 'rank_icir': '0.241', 'weight': '0.068'}

	Recorder: 361eddb817fc45a7802a4dd98e0587e9

		Model: {'id': '361eddb817fc45a7802a4dd98e0587e9', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.04, 'ICIR': 0.26, 'Rank IC': 0.035, 'Rank ICIR': 0.244}, 'data_train_vec': ['2025-04-16', '2026-01-15'], 'train_time_vec': ['2026-04-16', '2026-04-16'], 'rank_icir': '0.244', 'weight': '0.069'}
