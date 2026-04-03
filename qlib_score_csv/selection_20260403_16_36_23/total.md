# params 
 {'predict_dates': [{'start': '2026-04-03', 'end': '2026-04-03'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260403_16 771849695242150216 (Recorders: 3/5)

	Recorder: d20b2ee93d684a21a2e333347532d715

		Model: {'id': 'd20b2ee93d684a21a2e333347532d715', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.077, 'Rank IC': 0.027, 'Rank ICIR': 0.153}, 'data_train_vec': ['2021-04-03', '2025-01-02'], 'train_time_vec': ['2026-04-03', '2026-04-03'], 'rank_icir': '0.153', 'weight': '0.046'}

	Recorder: 396c8047cc584cf1a87d77595d758f2c

		Model: {'id': '396c8047cc584cf1a87d77595d758f2c', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.204, 'Rank IC': 0.048, 'Rank ICIR': 0.324}, 'data_train_vec': ['2023-04-03', '2025-07-02'], 'train_time_vec': ['2026-04-03', '2026-04-03'], 'rank_icir': '0.324', 'weight': '0.097'}

	Recorder: 55f4f035efe74bd98cd7c5776c8719cf

		Model: {'id': '55f4f035efe74bd98cd7c5776c8719cf', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.13, 'Rank IC': 0.047, 'Rank ICIR': 0.392}, 'data_train_vec': ['2024-04-03', '2025-10-02'], 'train_time_vec': ['2026-04-03', '2026-04-03'], 'rank_icir': '0.392', 'weight': '0.117'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260403_16 140353724246952782 (Recorders: 3/5)

	Recorder: 75ecc9ca651244e0b14d0516a898b7de

		Model: {'id': '75ecc9ca651244e0b14d0516a898b7de', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.027, 'Rank IC': 0.029, 'Rank ICIR': 0.178}, 'data_train_vec': ['2021-04-03', '2025-01-02'], 'train_time_vec': ['2026-04-03', '2026-04-03'], 'rank_icir': '0.178', 'weight': '0.053'}

	Recorder: a1718d3e314f47fb8c709d4c266a9dbc

		Model: {'id': 'a1718d3e314f47fb8c709d4c266a9dbc', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.063, 'Rank IC': 0.052, 'Rank ICIR': 0.305}, 'data_train_vec': ['2023-04-03', '2025-07-02'], 'train_time_vec': ['2026-04-03', '2026-04-03'], 'rank_icir': '0.305', 'weight': '0.091'}

	Recorder: e27fc98133c445719e6c660539f5bf59

		Model: {'id': 'e27fc98133c445719e6c660539f5bf59', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.181, 'Rank IC': 0.027, 'Rank ICIR': 0.234}, 'data_train_vec': ['2024-04-03', '2025-10-02'], 'train_time_vec': ['2026-04-03', '2026-04-03'], 'rank_icir': '0.234', 'weight': '0.070'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260403_13 614946197663984951 (Recorders: 3/5)

	Recorder: 0b01b161df434b81a73bb1401597c24f

		Model: {'id': '0b01b161df434b81a73bb1401597c24f', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.115, 'Rank IC': 0.039, 'Rank ICIR': 0.216}, 'data_train_vec': ['2021-04-03', '2025-01-02'], 'train_time_vec': ['2026-04-03', '2026-04-03'], 'rank_icir': '0.216', 'weight': '0.064'}

	Recorder: d375e72928314886bc042455066918a7

		Model: {'id': 'd375e72928314886bc042455066918a7', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.089, 'Rank IC': 0.05, 'Rank ICIR': 0.293}, 'data_train_vec': ['2023-04-03', '2025-07-02'], 'train_time_vec': ['2026-04-03', '2026-04-03'], 'rank_icir': '0.293', 'weight': '0.087'}

	Recorder: 2201a12057284e1c933ba233ae616d4c

		Model: {'id': '2201a12057284e1c933ba233ae616d4c', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.289, 'Rank IC': 0.037, 'Rank ICIR': 0.373}, 'data_train_vec': ['2024-04-03', '2025-10-02'], 'train_time_vec': ['2026-04-03', '2026-04-03'], 'rank_icir': '0.373', 'weight': '0.111'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260403_13 937870712036266938 (Recorders: 3/5)

	Recorder: c2110a63c9b54a85b28c0f58c60f76ab

		Model: {'id': 'c2110a63c9b54a85b28c0f58c60f76ab', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.106, 'Rank IC': 0.024, 'Rank ICIR': 0.199}, 'data_train_vec': ['2021-04-03', '2025-01-02'], 'train_time_vec': ['2026-04-03', '2026-04-03'], 'rank_icir': '0.199', 'weight': '0.059'}

	Recorder: d2cd853088094394ac2cbc929c49965d

		Model: {'id': 'd2cd853088094394ac2cbc929c49965d', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.028, 'Rank IC': 0.021, 'Rank ICIR': 0.177}, 'data_train_vec': ['2022-04-03', '2025-04-02'], 'train_time_vec': ['2026-04-03', '2026-04-03'], 'rank_icir': '0.177', 'weight': '0.053'}

	Recorder: b137971cc48b4c9d94834d4baea43efe

		Model: {'id': 'b137971cc48b4c9d94834d4baea43efe', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.097, 'Rank IC': 0.039, 'Rank ICIR': 0.33}, 'data_train_vec': ['2023-04-03', '2025-07-02'], 'train_time_vec': ['2026-04-03', '2026-04-03'], 'rank_icir': '0.330', 'weight': '0.099'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260403_13 674794267125758276 (Recorders: 1/5)

	Recorder: 3fa7e5f48cc24977b6a8ab5bbc4f8554

		Model: {'id': '3fa7e5f48cc24977b6a8ab5bbc4f8554', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.043, 'Rank IC': 0.031, 'Rank ICIR': 0.175}, 'data_train_vec': ['2022-04-03', '2025-04-02'], 'train_time_vec': ['2026-04-03', '2026-04-03'], 'rank_icir': '0.175', 'weight': '0.052'}
