# params 
 {'predict_dates': [{'start': '2026-04-14', 'end': '2026-04-14'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260415_16 267855066873189428 (Recorders: 2/5)

	Recorder: b67c666c697842e78c0cbde46dd450bf

		Model: {'id': 'b67c666c697842e78c0cbde46dd450bf', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.044, 'Rank IC': 0.035, 'Rank ICIR': 0.214}, 'data_train_vec': ['2023-04-15', '2025-07-14'], 'train_time_vec': ['2026-04-15', '2026-04-15'], 'rank_icir': '0.214', 'weight': '0.057'}

	Recorder: a7f50608de2e4bf391b1cc84a38012fc

		Model: {'id': 'a7f50608de2e4bf391b1cc84a38012fc', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.056, 'ICIR': 0.403, 'Rank IC': 0.052, 'Rank ICIR': 0.373}, 'data_train_vec': ['2025-04-15', '2026-01-14'], 'train_time_vec': ['2026-04-15', '2026-04-15'], 'rank_icir': '0.373', 'weight': '0.100'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260415_16 300591115696936794 (Recorders: 2/5)

	Recorder: afd3773f2b9647f494fcdfaad1bbeb2f

		Model: {'id': 'afd3773f2b9647f494fcdfaad1bbeb2f', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.251, 'Rank IC': 0.035, 'Rank ICIR': 0.337}, 'data_train_vec': ['2024-04-15', '2025-10-14'], 'train_time_vec': ['2026-04-15', '2026-04-15'], 'rank_icir': '0.337', 'weight': '0.090'}

	Recorder: 4c9c6162322844729d25cf3775a8f6e3

		Model: {'id': '4c9c6162322844729d25cf3775a8f6e3', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.038, 'ICIR': 0.28, 'Rank IC': 0.035, 'Rank ICIR': 0.219}, 'data_train_vec': ['2025-04-15', '2026-01-14'], 'train_time_vec': ['2026-04-15', '2026-04-15'], 'rank_icir': '0.219', 'weight': '0.059'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260415_14 365737585564303242 (Recorders: 4/5)

	Recorder: a96306b4c11b443a89550eade1dacd3c

		Model: {'id': 'a96306b4c11b443a89550eade1dacd3c', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.012, 'Rank IC': 0.023, 'Rank ICIR': 0.14}, 'data_train_vec': ['2021-04-15', '2025-01-14'], 'train_time_vec': ['2026-04-15', '2026-04-15'], 'rank_icir': '0.140', 'weight': '0.037'}

	Recorder: fdaf2579f70c4dbfbea6746841413133

		Model: {'id': 'fdaf2579f70c4dbfbea6746841413133', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.076, 'Rank IC': 0.047, 'Rank ICIR': 0.285}, 'data_train_vec': ['2023-04-15', '2025-07-14'], 'train_time_vec': ['2026-04-15', '2026-04-15'], 'rank_icir': '0.285', 'weight': '0.076'}

	Recorder: 726a1988d2fa40918d3cfe0fd4c98467

		Model: {'id': '726a1988d2fa40918d3cfe0fd4c98467', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.179, 'Rank IC': 0.024, 'Rank ICIR': 0.196}, 'data_train_vec': ['2024-04-15', '2025-10-14'], 'train_time_vec': ['2026-04-15', '2026-04-15'], 'rank_icir': '0.196', 'weight': '0.052'}

	Recorder: 115261d4c5f9404ba6abd27fff931bff

		Model: {'id': '115261d4c5f9404ba6abd27fff931bff', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.049, 'ICIR': 0.263, 'Rank IC': 0.041, 'Rank ICIR': 0.217}, 'data_train_vec': ['2025-04-15', '2026-01-14'], 'train_time_vec': ['2026-04-15', '2026-04-15'], 'rank_icir': '0.217', 'weight': '0.058'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260415_14 235434317457644547 (Recorders: 4/5)

	Recorder: 202c3af713694a1c956b65c7b5d5f3c2

		Model: {'id': '202c3af713694a1c956b65c7b5d5f3c2', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.052, 'Rank IC': 0.018, 'Rank ICIR': 0.164}, 'data_train_vec': ['2021-04-15', '2025-01-14'], 'train_time_vec': ['2026-04-15', '2026-04-15'], 'rank_icir': '0.164', 'weight': '0.044'}

	Recorder: 77edcb835c8f4abb9b21bd05a022e1b3

		Model: {'id': '77edcb835c8f4abb9b21bd05a022e1b3', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.061, 'Rank IC': 0.036, 'Rank ICIR': 0.307}, 'data_train_vec': ['2023-04-15', '2025-07-14'], 'train_time_vec': ['2026-04-15', '2026-04-15'], 'rank_icir': '0.307', 'weight': '0.082'}

	Recorder: 6ea7f1f3bcb34672b5589d0768ec54d6

		Model: {'id': '6ea7f1f3bcb34672b5589d0768ec54d6', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.075, 'Rank IC': 0.015, 'Rank ICIR': 0.128}, 'data_train_vec': ['2024-04-15', '2025-10-14'], 'train_time_vec': ['2026-04-15', '2026-04-15'], 'rank_icir': '0.128', 'weight': '0.034'}

	Recorder: 6e7a6abcb91e48468b8c677365719480

		Model: {'id': '6e7a6abcb91e48468b8c677365719480', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.075, 'ICIR': 0.479, 'Rank IC': 0.059, 'Rank ICIR': 0.362}, 'data_train_vec': ['2025-04-15', '2026-01-14'], 'train_time_vec': ['2026-04-15', '2026-04-15'], 'rank_icir': '0.362', 'weight': '0.097'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260415_14 541690772154613294 (Recorders: 3/5)

	Recorder: cfbdfe93075646d79f9b11cf847ca737

		Model: {'id': 'cfbdfe93075646d79f9b11cf847ca737', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.096, 'Rank IC': 0.044, 'Rank ICIR': 0.272}, 'data_train_vec': ['2023-04-15', '2025-07-14'], 'train_time_vec': ['2026-04-15', '2026-04-15'], 'rank_icir': '0.272', 'weight': '0.073'}

	Recorder: a448772915cd4ae8b6fe42b95b4e206f

		Model: {'id': 'a448772915cd4ae8b6fe42b95b4e206f', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.045, 'Rank IC': 0.038, 'Rank ICIR': 0.338}, 'data_train_vec': ['2024-04-15', '2025-10-14'], 'train_time_vec': ['2026-04-15', '2026-04-15'], 'rank_icir': '0.338', 'weight': '0.090'}

	Recorder: b4536eca74404eba8a57a0962890ae81

		Model: {'id': 'b4536eca74404eba8a57a0962890ae81', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.046, 'ICIR': 0.297, 'Rank IC': 0.028, 'Rank ICIR': 0.19}, 'data_train_vec': ['2025-04-15', '2026-01-14'], 'train_time_vec': ['2026-04-15', '2026-04-15'], 'rank_icir': '0.190', 'weight': '0.051'}
