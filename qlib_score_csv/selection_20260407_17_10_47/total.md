# params 
 {'predict_dates': [{'start': '2026-04-07', 'end': '2026-04-07'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260407_16 155086909819739693 (Recorders: 4/5)

	Recorder: b3196692ae794450934857c19a5e2c57

		Model: {'id': 'b3196692ae794450934857c19a5e2c57', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.048, 'Rank IC': 0.025, 'Rank ICIR': 0.135}, 'data_train_vec': ['2021-04-07', '2025-01-06'], 'train_time_vec': ['2026-04-07', '2026-04-07'], 'rank_icir': '0.135', 'weight': '0.036'}

	Recorder: af202d3f59924829ac889ea9dce01bab

		Model: {'id': 'af202d3f59924829ac889ea9dce01bab', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.011, 'Rank IC': 0.034, 'Rank ICIR': 0.182}, 'data_train_vec': ['2022-04-07', '2025-04-06'], 'train_time_vec': ['2026-04-07', '2026-04-07'], 'rank_icir': '0.182', 'weight': '0.048'}

	Recorder: 282495d2b83a4cc28e2e012f9db32c99

		Model: {'id': '282495d2b83a4cc28e2e012f9db32c99', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.072, 'Rank IC': 0.048, 'Rank ICIR': 0.364}, 'data_train_vec': ['2023-04-07', '2025-07-06'], 'train_time_vec': ['2026-04-07', '2026-04-07'], 'rank_icir': '0.364', 'weight': '0.096'}

	Recorder: 42b042aba83d476d9aef464f039300cc

		Model: {'id': '42b042aba83d476d9aef464f039300cc', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.034, 'ICIR': 0.322, 'Rank IC': 0.039, 'Rank ICIR': 0.336}, 'data_train_vec': ['2024-04-07', '2025-10-06'], 'train_time_vec': ['2026-04-07', '2026-04-07'], 'rank_icir': '0.336', 'weight': '0.089'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260407_16 931884641303738395 (Recorders: 1/5)

	Recorder: 088880180db74b1da78d54f69721539b

		Model: {'id': '088880180db74b1da78d54f69721539b', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.302, 'Rank IC': 0.037, 'Rank ICIR': 0.312}, 'data_train_vec': ['2024-04-07', '2025-10-06'], 'train_time_vec': ['2026-04-07', '2026-04-07'], 'rank_icir': '0.312', 'weight': '0.082'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260407_14 338797886413787142 (Recorders: 4/5)

	Recorder: 0795ab15d559430abd7566d1b91f6826

		Model: {'id': '0795ab15d559430abd7566d1b91f6826', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.098, 'Rank IC': 0.035, 'Rank ICIR': 0.194}, 'data_train_vec': ['2021-04-07', '2025-01-06'], 'train_time_vec': ['2026-04-07', '2026-04-07'], 'rank_icir': '0.194', 'weight': '0.051'}

	Recorder: afd391c811ee490092bd73c79a88d398

		Model: {'id': 'afd391c811ee490092bd73c79a88d398', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.019, 'Rank IC': 0.032, 'Rank ICIR': 0.167}, 'data_train_vec': ['2022-04-07', '2025-04-06'], 'train_time_vec': ['2026-04-07', '2026-04-07'], 'rank_icir': '0.167', 'weight': '0.044'}

	Recorder: 5a0fe064c6894044886c493dffa16fac

		Model: {'id': '5a0fe064c6894044886c493dffa16fac', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.129, 'Rank IC': 0.054, 'Rank ICIR': 0.318}, 'data_train_vec': ['2023-04-07', '2025-07-06'], 'train_time_vec': ['2026-04-07', '2026-04-07'], 'rank_icir': '0.318', 'weight': '0.084'}

	Recorder: e664cb1985964b018eb13a569f2d5484

		Model: {'id': 'e664cb1985964b018eb13a569f2d5484', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.348, 'Rank IC': 0.036, 'Rank ICIR': 0.347}, 'data_train_vec': ['2024-04-07', '2025-10-06'], 'train_time_vec': ['2026-04-07', '2026-04-07'], 'rank_icir': '0.347', 'weight': '0.091'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260407_14 471294604247579357 (Recorders: 3/5)

	Recorder: 252f5d443bdb43b894dd882946eeba5f

		Model: {'id': '252f5d443bdb43b894dd882946eeba5f', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.11, 'Rank IC': 0.023, 'Rank ICIR': 0.187}, 'data_train_vec': ['2021-04-07', '2025-01-06'], 'train_time_vec': ['2026-04-07', '2026-04-07'], 'rank_icir': '0.187', 'weight': '0.049'}

	Recorder: 751d9b530b1f43699008a3b3d8511396

		Model: {'id': '751d9b530b1f43699008a3b3d8511396', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.054, 'Rank IC': 0.024, 'Rank ICIR': 0.204}, 'data_train_vec': ['2022-04-07', '2025-04-06'], 'train_time_vec': ['2026-04-07', '2026-04-07'], 'rank_icir': '0.204', 'weight': '0.054'}

	Recorder: f3ce55f08ca9418ca92b435dbdb9edbc

		Model: {'id': 'f3ce55f08ca9418ca92b435dbdb9edbc', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.101, 'Rank IC': 0.039, 'Rank ICIR': 0.338}, 'data_train_vec': ['2023-04-07', '2025-07-06'], 'train_time_vec': ['2026-04-07', '2026-04-07'], 'rank_icir': '0.338', 'weight': '0.089'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260407_13 180410923689510239 (Recorders: 3/5)

	Recorder: d1bea3d7585744d888fd1d3803f672e8

		Model: {'id': 'd1bea3d7585744d888fd1d3803f672e8', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.048, 'Rank IC': 0.028, 'Rank ICIR': 0.151}, 'data_train_vec': ['2021-04-07', '2025-01-06'], 'train_time_vec': ['2026-04-07', '2026-04-07'], 'rank_icir': '0.151', 'weight': '0.040'}

	Recorder: adda0228d443433f8dbce854dca93db6

		Model: {'id': 'adda0228d443433f8dbce854dca93db6', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.087, 'Rank IC': 0.048, 'Rank ICIR': 0.286}, 'data_train_vec': ['2023-04-07', '2025-07-06'], 'train_time_vec': ['2026-04-07', '2026-04-07'], 'rank_icir': '0.286', 'weight': '0.075'}

	Recorder: a1e94aa0dfaa4e00a1edcd2b6d6676b7

		Model: {'id': 'a1e94aa0dfaa4e00a1edcd2b6d6676b7', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.287, 'Rank IC': 0.032, 'Rank ICIR': 0.273}, 'data_train_vec': ['2024-04-07', '2025-10-06'], 'train_time_vec': ['2026-04-07', '2026-04-07'], 'rank_icir': '0.273', 'weight': '0.072'}
