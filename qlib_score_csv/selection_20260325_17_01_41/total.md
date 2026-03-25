# params 
 {'predict_dates': [{'start': '2026-03-25', 'end': '2026-03-25'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260325_16 106320528813672859 (Recorders: 3/5)

	Recorder: 12b9854151a54b12abb9fc6333ab81a3

		Model: {'id': '12b9854151a54b12abb9fc6333ab81a3', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.045, 'Rank IC': 0.021, 'Rank ICIR': 0.159}, 'data_train_vec': ['2021-03-25', '2024-12-24'], 'train_time_vec': ['2026-03-25', '2026-03-25'], 'rank_icir': '0.159', 'weight': '0.032'}

	Recorder: 4678ce2047c4495ca538870badc89099

		Model: {'id': '4678ce2047c4495ca538870badc89099', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.106, 'Rank IC': 0.038, 'Rank ICIR': 0.304}, 'data_train_vec': ['2024-03-25', '2025-09-24'], 'train_time_vec': ['2026-03-25', '2026-03-25'], 'rank_icir': '0.304', 'weight': '0.062'}

	Recorder: 0a2823689bd8400fbdb42a7ff547ec72

		Model: {'id': '0a2823689bd8400fbdb42a7ff547ec72', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.169, 'Rank IC': 0.017, 'Rank ICIR': 0.115}, 'data_train_vec': ['2025-03-25', '2025-12-24'], 'train_time_vec': ['2026-03-25', '2026-03-25'], 'rank_icir': '0.115', 'weight': '0.023'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260325_16 964741167322393124 (Recorders: 2/5)

	Recorder: e77f59e3a19c4ae9b9f0cff2fa1ff970

		Model: {'id': 'e77f59e3a19c4ae9b9f0cff2fa1ff970', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.06, 'Rank IC': 0.026, 'Rank ICIR': 0.189}, 'data_train_vec': ['2021-03-25', '2024-12-24'], 'train_time_vec': ['2026-03-25', '2026-03-25'], 'rank_icir': '0.189', 'weight': '0.038'}

	Recorder: 3d99372173b34bceaf3ce4d19f35a26e

		Model: {'id': '3d99372173b34bceaf3ce4d19f35a26e', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.352, 'Rank IC': 0.051, 'Rank ICIR': 0.441}, 'data_train_vec': ['2024-03-25', '2025-09-24'], 'train_time_vec': ['2026-03-25', '2026-03-25'], 'rank_icir': '0.441', 'weight': '0.090'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260325_13 835901002654497163 (Recorders: 4/5)

	Recorder: 96c1cd16989d460eac311e28acf4ad58

		Model: {'id': '96c1cd16989d460eac311e28acf4ad58', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.125, 'Rank IC': 0.037, 'Rank ICIR': 0.217}, 'data_train_vec': ['2021-03-25', '2024-12-24'], 'train_time_vec': ['2026-03-25', '2026-03-25'], 'rank_icir': '0.217', 'weight': '0.044'}

	Recorder: a3e9701db23a46bf8b4b324f5d424039

		Model: {'id': 'a3e9701db23a46bf8b4b324f5d424039', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.019, 'Rank IC': 0.039, 'Rank ICIR': 0.225}, 'data_train_vec': ['2023-03-25', '2025-06-24'], 'train_time_vec': ['2026-03-25', '2026-03-25'], 'rank_icir': '0.225', 'weight': '0.046'}

	Recorder: 8b80ffa0dafb4204acdf8af00c12e554

		Model: {'id': '8b80ffa0dafb4204acdf8af00c12e554', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.045, 'ICIR': 0.418, 'Rank IC': 0.056, 'Rank ICIR': 0.472}, 'data_train_vec': ['2024-03-25', '2025-09-24'], 'train_time_vec': ['2026-03-25', '2026-03-25'], 'rank_icir': '0.472', 'weight': '0.096'}

	Recorder: fd0cf5990cfa49178e0e6f419d532852

		Model: {'id': 'fd0cf5990cfa49178e0e6f419d532852', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.136, 'Rank IC': 0.021, 'Rank ICIR': 0.181}, 'data_train_vec': ['2025-03-25', '2025-12-24'], 'train_time_vec': ['2026-03-25', '2026-03-25'], 'rank_icir': '0.181', 'weight': '0.037'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260325_13 308965150223853316 (Recorders: 5/5)

	Recorder: 5e47375ec86642829701db093f99daa4

		Model: {'id': '5e47375ec86642829701db093f99daa4', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.169, 'Rank IC': 0.027, 'Rank ICIR': 0.233}, 'data_train_vec': ['2021-03-25', '2024-12-24'], 'train_time_vec': ['2026-03-25', '2026-03-25'], 'rank_icir': '0.233', 'weight': '0.047'}

	Recorder: 0a1fc3fa42024f219c76b5b79114ab6b

		Model: {'id': '0a1fc3fa42024f219c76b5b79114ab6b', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.035, 'Rank IC': 0.019, 'Rank ICIR': 0.162}, 'data_train_vec': ['2022-03-25', '2025-03-24'], 'train_time_vec': ['2026-03-25', '2026-03-25'], 'rank_icir': '0.162', 'weight': '0.033'}

	Recorder: 699f9434c7a6440e96f11507b91aa41a

		Model: {'id': '699f9434c7a6440e96f11507b91aa41a', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.127, 'Rank IC': 0.038, 'Rank ICIR': 0.341}, 'data_train_vec': ['2023-03-25', '2025-06-24'], 'train_time_vec': ['2026-03-25', '2026-03-25'], 'rank_icir': '0.341', 'weight': '0.069'}

	Recorder: 84f92714bba141c98caab84483e1ba75

		Model: {'id': '84f92714bba141c98caab84483e1ba75', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.148, 'Rank IC': 0.025, 'Rank ICIR': 0.214}, 'data_train_vec': ['2024-03-25', '2025-09-24'], 'train_time_vec': ['2026-03-25', '2026-03-25'], 'rank_icir': '0.214', 'weight': '0.044'}

	Recorder: b3431fd1ce354ef8b3c72a7a7cbae21e

		Model: {'id': 'b3431fd1ce354ef8b3c72a7a7cbae21e', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.173, 'Rank IC': 0.025, 'Rank ICIR': 0.242}, 'data_train_vec': ['2025-03-25', '2025-12-24'], 'train_time_vec': ['2026-03-25', '2026-03-25'], 'rank_icir': '0.242', 'weight': '0.049'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260325_13 508583181902795781 (Recorders: 5/5)

	Recorder: e5d82b62490c439a90875fef23a7ae58

		Model: {'id': 'e5d82b62490c439a90875fef23a7ae58', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.102, 'Rank IC': 0.039, 'Rank ICIR': 0.216}, 'data_train_vec': ['2021-03-25', '2024-12-24'], 'train_time_vec': ['2026-03-25', '2026-03-25'], 'rank_icir': '0.216', 'weight': '0.044'}

	Recorder: 013fa77d9d014b0c948528111d55192d

		Model: {'id': '013fa77d9d014b0c948528111d55192d', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.045, 'Rank IC': 0.014, 'Rank ICIR': 0.073}, 'data_train_vec': ['2022-03-25', '2025-03-24'], 'train_time_vec': ['2026-03-25', '2026-03-25'], 'rank_icir': '0.073', 'weight': '0.015'}

	Recorder: 04ee0bdb295b4e46a80aec7b55f8ac4c

		Model: {'id': '04ee0bdb295b4e46a80aec7b55f8ac4c', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.032, 'Rank IC': 0.032, 'Rank ICIR': 0.185}, 'data_train_vec': ['2023-03-25', '2025-06-24'], 'train_time_vec': ['2026-03-25', '2026-03-25'], 'rank_icir': '0.185', 'weight': '0.038'}

	Recorder: 0b3d4c4cab814624a56344ca636b3b7a

		Model: {'id': '0b3d4c4cab814624a56344ca636b3b7a', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.06, 'Rank IC': 0.041, 'Rank ICIR': 0.393}, 'data_train_vec': ['2024-03-25', '2025-09-24'], 'train_time_vec': ['2026-03-25', '2026-03-25'], 'rank_icir': '0.393', 'weight': '0.080'}

	Recorder: 59d916e1806641ce9f1890bd22b2e4fe

		Model: {'id': '59d916e1806641ce9f1890bd22b2e4fe', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.252, 'Rank IC': 0.04, 'Rank ICIR': 0.556}, 'data_train_vec': ['2025-03-25', '2025-12-24'], 'train_time_vec': ['2026-03-25', '2026-03-25'], 'rank_icir': '0.556', 'weight': '0.113'}
