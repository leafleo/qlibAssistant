# params 
 {'predict_dates': [{'start': '2026-05-26', 'end': '2026-05-26'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260526_18 780851847416074224 (Recorders: 3/5)

	Recorder: 561bcd58a3db4333b29e420d59821886

		Model: {'id': '561bcd58a3db4333b29e420d59821886', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.032, 'Rank IC': 0.029, 'Rank ICIR': 0.167}, 'data_train_vec': ['2022-05-26', '2025-05-25'], 'train_time_vec': ['2026-05-26', '2026-05-26'], 'rank_icir': '0.167', 'weight': '0.051'}

	Recorder: 0878e23f1e3647f8887210b685a5a554

		Model: {'id': '0878e23f1e3647f8887210b685a5a554', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.057, 'Rank IC': 0.028, 'Rank ICIR': 0.177}, 'data_train_vec': ['2023-05-26', '2025-08-25'], 'train_time_vec': ['2026-05-26', '2026-05-26'], 'rank_icir': '0.177', 'weight': '0.054'}

	Recorder: eb018ca513c64eb58b0b76c1a89ae675

		Model: {'id': 'eb018ca513c64eb58b0b76c1a89ae675', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.042, 'ICIR': 0.193, 'Rank IC': 0.035, 'Rank ICIR': 0.191}, 'data_train_vec': ['2025-05-26', '2026-02-25'], 'train_time_vec': ['2026-05-26', '2026-05-26'], 'rank_icir': '0.191', 'weight': '0.058'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260526_18 660357164491050718 (Recorders: 3/5)

	Recorder: 4491753103b04f25aacc33aa4f2bdc1a

		Model: {'id': '4491753103b04f25aacc33aa4f2bdc1a', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.198, 'Rank IC': 0.029, 'Rank ICIR': 0.236}, 'data_train_vec': ['2023-05-26', '2025-08-25'], 'train_time_vec': ['2026-05-26', '2026-05-26'], 'rank_icir': '0.236', 'weight': '0.072'}

	Recorder: 6661f3eb9ecb4721bccfebbd57ba2388

		Model: {'id': '6661f3eb9ecb4721bccfebbd57ba2388', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.2, 'Rank IC': 0.01, 'Rank ICIR': 0.084}, 'data_train_vec': ['2024-05-26', '2025-11-25'], 'train_time_vec': ['2026-05-26', '2026-05-26'], 'rank_icir': '0.084', 'weight': '0.025'}

	Recorder: b8f2b9bc7c13431dad15b51490e03a8c

		Model: {'id': 'b8f2b9bc7c13431dad15b51490e03a8c', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.085, 'ICIR': 0.451, 'Rank IC': 0.045, 'Rank ICIR': 0.217}, 'data_train_vec': ['2025-05-26', '2026-02-25'], 'train_time_vec': ['2026-05-26', '2026-05-26'], 'rank_icir': '0.217', 'weight': '0.066'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260526_16 251487868483354103 (Recorders: 4/5)

	Recorder: 1befa8bbddab4a3e983fb1a04783aa59

		Model: {'id': '1befa8bbddab4a3e983fb1a04783aa59', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.035, 'Rank IC': 0.029, 'Rank ICIR': 0.202}, 'data_train_vec': ['2021-05-26', '2025-02-25'], 'train_time_vec': ['2026-05-26', '2026-05-26'], 'rank_icir': '0.202', 'weight': '0.061'}

	Recorder: 5eb42ddbcb4d4bf78fc3b839dac84d7e

		Model: {'id': '5eb42ddbcb4d4bf78fc3b839dac84d7e', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.052, 'Rank IC': 0.038, 'Rank ICIR': 0.221}, 'data_train_vec': ['2022-05-26', '2025-05-25'], 'train_time_vec': ['2026-05-26', '2026-05-26'], 'rank_icir': '0.221', 'weight': '0.067'}

	Recorder: 271310707ece43ffae505a5acbc06e41

		Model: {'id': '271310707ece43ffae505a5acbc06e41', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.181, 'Rank IC': 0.038, 'Rank ICIR': 0.26}, 'data_train_vec': ['2023-05-26', '2025-08-25'], 'train_time_vec': ['2026-05-26', '2026-05-26'], 'rank_icir': '0.260', 'weight': '0.079'}

	Recorder: 1a690aa244674b58bbbbd82c08f19ed8

		Model: {'id': '1a690aa244674b58bbbbd82c08f19ed8', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.056, 'ICIR': 0.3, 'Rank IC': 0.031, 'Rank ICIR': 0.164}, 'data_train_vec': ['2025-05-26', '2026-02-25'], 'train_time_vec': ['2026-05-26', '2026-05-26'], 'rank_icir': '0.164', 'weight': '0.050'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260526_16 214824068604195090 (Recorders: 4/5)

	Recorder: dd91145d31614c56a0867c06ebc9af4e

		Model: {'id': 'dd91145d31614c56a0867c06ebc9af4e', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.059, 'Rank IC': 0.032, 'Rank ICIR': 0.278}, 'data_train_vec': ['2021-05-26', '2025-02-25'], 'train_time_vec': ['2026-05-26', '2026-05-26'], 'rank_icir': '0.278', 'weight': '0.084'}

	Recorder: 107e05b3a4ab4dbca74b7b2e0b444af9

		Model: {'id': '107e05b3a4ab4dbca74b7b2e0b444af9', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.108, 'Rank IC': 0.038, 'Rank ICIR': 0.345}, 'data_train_vec': ['2023-05-26', '2025-08-25'], 'train_time_vec': ['2026-05-26', '2026-05-26'], 'rank_icir': '0.345', 'weight': '0.105'}

	Recorder: d932b88ce48d47ccbad5df79271cf275

		Model: {'id': 'd932b88ce48d47ccbad5df79271cf275', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.023, 'Rank IC': 0.011, 'Rank ICIR': 0.087}, 'data_train_vec': ['2024-05-26', '2025-11-25'], 'train_time_vec': ['2026-05-26', '2026-05-26'], 'rank_icir': '0.087', 'weight': '0.026'}

	Recorder: b498216a77964aa3a2983eb11a71015d

		Model: {'id': 'b498216a77964aa3a2983eb11a71015d', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.104, 'ICIR': 0.604, 'Rank IC': 0.081, 'Rank ICIR': 0.412}, 'data_train_vec': ['2025-05-26', '2026-02-25'], 'train_time_vec': ['2026-05-26', '2026-05-26'], 'rank_icir': '0.412', 'weight': '0.125'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260526_16 165122556411775631 (Recorders: 1/5)

	Recorder: 5a3da660f81a4c609cb2af7bf7518d8d

		Model: {'id': '5a3da660f81a4c609cb2af7bf7518d8d', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.052, 'ICIR': 0.302, 'Rank IC': 0.038, 'Rank ICIR': 0.255}, 'data_train_vec': ['2025-05-26', '2026-02-25'], 'train_time_vec': ['2026-05-26', '2026-05-26'], 'rank_icir': '0.255', 'weight': '0.077'}
