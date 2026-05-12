# params 
 {'predict_dates': [{'start': '2026-05-12', 'end': '2026-05-12'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260512_17 324571399283404725 (Recorders: 4/5)

	Recorder: 33503d3d5f3845c8bb1c75c2e242f2e3

		Model: {'id': '33503d3d5f3845c8bb1c75c2e242f2e3', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.094, 'Rank IC': 0.013, 'Rank ICIR': 0.081}, 'data_train_vec': ['2022-05-12', '2025-05-11'], 'train_time_vec': ['2026-05-12', '2026-05-12'], 'rank_icir': '0.081', 'weight': '0.028'}

	Recorder: 95c16a103ede4d87980dd38293ef27cb

		Model: {'id': '95c16a103ede4d87980dd38293ef27cb', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.107, 'Rank IC': 0.02, 'Rank ICIR': 0.136}, 'data_train_vec': ['2023-05-12', '2025-08-11'], 'train_time_vec': ['2026-05-12', '2026-05-12'], 'rank_icir': '0.136', 'weight': '0.047'}

	Recorder: 2d1febadb31742be97f2955f584673e2

		Model: {'id': '2d1febadb31742be97f2955f584673e2', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.087, 'Rank IC': 0.016, 'Rank ICIR': 0.135}, 'data_train_vec': ['2024-05-12', '2025-11-11'], 'train_time_vec': ['2026-05-12', '2026-05-12'], 'rank_icir': '0.135', 'weight': '0.046'}

	Recorder: 93feca5ed34f4ad7b40c1e76589d1611

		Model: {'id': '93feca5ed34f4ad7b40c1e76589d1611', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.056, 'ICIR': 0.42, 'Rank IC': 0.018, 'Rank ICIR': 0.145}, 'data_train_vec': ['2025-05-12', '2026-02-11'], 'train_time_vec': ['2026-05-12', '2026-05-12'], 'rank_icir': '0.145', 'weight': '0.050'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260512_17 551973586620377393 (Recorders: 3/5)

	Recorder: 705dc84b751c49fb9a9304e29a5dc67f

		Model: {'id': '705dc84b751c49fb9a9304e29a5dc67f', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.079, 'Rank IC': 0.018, 'Rank ICIR': 0.159}, 'data_train_vec': ['2023-05-12', '2025-08-11'], 'train_time_vec': ['2026-05-12', '2026-05-12'], 'rank_icir': '0.159', 'weight': '0.054'}

	Recorder: 6e5f76870fed42339e324b4cca9301cd

		Model: {'id': '6e5f76870fed42339e324b4cca9301cd', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.146, 'Rank IC': 0.013, 'Rank ICIR': 0.108}, 'data_train_vec': ['2024-05-12', '2025-11-11'], 'train_time_vec': ['2026-05-12', '2026-05-12'], 'rank_icir': '0.108', 'weight': '0.037'}

	Recorder: 0ef9a145ddd541c7836a296a626b31ab

		Model: {'id': '0ef9a145ddd541c7836a296a626b31ab', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.075, 'ICIR': 0.586, 'Rank IC': 0.024, 'Rank ICIR': 0.217}, 'data_train_vec': ['2025-05-12', '2026-02-11'], 'train_time_vec': ['2026-05-12', '2026-05-12'], 'rank_icir': '0.217', 'weight': '0.074'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260512_14 246339121684694607 (Recorders: 4/5)

	Recorder: 490a622bf2954989bd9350f05150e70c

		Model: {'id': '490a622bf2954989bd9350f05150e70c', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.028, 'Rank IC': 0.03, 'Rank ICIR': 0.171}, 'data_train_vec': ['2022-05-12', '2025-05-11'], 'train_time_vec': ['2026-05-12', '2026-05-12'], 'rank_icir': '0.171', 'weight': '0.059'}

	Recorder: 501044237f2843748235bbc7664f9a92

		Model: {'id': '501044237f2843748235bbc7664f9a92', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.078, 'Rank IC': 0.028, 'Rank ICIR': 0.188}, 'data_train_vec': ['2023-05-12', '2025-08-11'], 'train_time_vec': ['2026-05-12', '2026-05-12'], 'rank_icir': '0.188', 'weight': '0.064'}

	Recorder: 4fa3ef8e759c4af5927f5f4cc8b1d0cd

		Model: {'id': '4fa3ef8e759c4af5927f5f4cc8b1d0cd', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.023, 'Rank IC': 0.004, 'Rank ICIR': 0.034}, 'data_train_vec': ['2024-05-12', '2025-11-11'], 'train_time_vec': ['2026-05-12', '2026-05-12'], 'rank_icir': '0.034', 'weight': '0.012'}

	Recorder: 0192c0f2ba14473498043471ffbc822e

		Model: {'id': '0192c0f2ba14473498043471ffbc822e', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.064, 'ICIR': 0.54, 'Rank IC': 0.021, 'Rank ICIR': 0.2}, 'data_train_vec': ['2025-05-12', '2026-02-11'], 'train_time_vec': ['2026-05-12', '2026-05-12'], 'rank_icir': '0.200', 'weight': '0.068'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260512_14 543378228876586802 (Recorders: 4/5)

	Recorder: a66867d731c34beda9ea8fbe6ed21d58

		Model: {'id': 'a66867d731c34beda9ea8fbe6ed21d58', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.014, 'Rank IC': 0.02, 'Rank ICIR': 0.188}, 'data_train_vec': ['2021-05-12', '2025-02-11'], 'train_time_vec': ['2026-05-12', '2026-05-12'], 'rank_icir': '0.188', 'weight': '0.064'}

	Recorder: d6e2c34784214f66aeaa0e6ddbb1cfb2

		Model: {'id': 'd6e2c34784214f66aeaa0e6ddbb1cfb2', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.017, 'Rank IC': 0.026, 'Rank ICIR': 0.225}, 'data_train_vec': ['2023-05-12', '2025-08-11'], 'train_time_vec': ['2026-05-12', '2026-05-12'], 'rank_icir': '0.225', 'weight': '0.077'}

	Recorder: b6648045df63403c8e71428f75698ef8

		Model: {'id': 'b6648045df63403c8e71428f75698ef8', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.08, 'Rank IC': 0.019, 'Rank ICIR': 0.164}, 'data_train_vec': ['2024-05-12', '2025-11-11'], 'train_time_vec': ['2026-05-12', '2026-05-12'], 'rank_icir': '0.164', 'weight': '0.056'}

	Recorder: 184592521d064902823e1696fc543c21

		Model: {'id': '184592521d064902823e1696fc543c21', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.047, 'ICIR': 0.622, 'Rank IC': 0.021, 'Rank ICIR': 0.247}, 'data_train_vec': ['2025-05-12', '2026-02-11'], 'train_time_vec': ['2026-05-12', '2026-05-12'], 'rank_icir': '0.247', 'weight': '0.085'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260512_14 382406238505038116 (Recorders: 4/5)

	Recorder: c870e27cd52240dd8ccea7cdf3ad7424

		Model: {'id': 'c870e27cd52240dd8ccea7cdf3ad7424', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.029, 'Rank IC': 0.011, 'Rank ICIR': 0.063}, 'data_train_vec': ['2022-05-12', '2025-05-11'], 'train_time_vec': ['2026-05-12', '2026-05-12'], 'rank_icir': '0.063', 'weight': '0.022'}

	Recorder: e530afa550c0465c83ca2d0396f68474

		Model: {'id': 'e530afa550c0465c83ca2d0396f68474', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.086, 'Rank IC': 0.024, 'Rank ICIR': 0.14}, 'data_train_vec': ['2023-05-12', '2025-08-11'], 'train_time_vec': ['2026-05-12', '2026-05-12'], 'rank_icir': '0.140', 'weight': '0.048'}

	Recorder: cf69055dec0b4924a627943184223e29

		Model: {'id': 'cf69055dec0b4924a627943184223e29', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.071, 'Rank IC': 0.008, 'Rank ICIR': 0.061}, 'data_train_vec': ['2024-05-12', '2025-11-11'], 'train_time_vec': ['2026-05-12', '2026-05-12'], 'rank_icir': '0.061', 'weight': '0.021'}

	Recorder: ebf42ddecedf4998b62df3030b172111

		Model: {'id': 'ebf42ddecedf4998b62df3030b172111', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.043, 'ICIR': 0.422, 'Rank IC': 0.019, 'Rank ICIR': 0.259}, 'data_train_vec': ['2025-05-12', '2026-02-11'], 'train_time_vec': ['2026-05-12', '2026-05-12'], 'rank_icir': '0.259', 'weight': '0.089'}
