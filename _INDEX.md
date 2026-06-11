# Siri / Apple Intelligence system-prompt corpus — 128 files

Two sources:
- **PLANNER_*** = on-disk agentic-Siri planner assets (IntelligenceFlowPlannerSupport.framework, NEW in 27). en_US canonical; full 36-locale tree in `../siri_planner_assets/`.
- **NNN_*** = system prompts embedded as __cstring in the dyld_shared_cache (per-feature AI models). `NEW27` = absent from 26.5.1.

| File | Status | Owning binary/framework | Preview |
|---|---|---|---|
| `001_NEW27_task_overview.txt` | NEW27 | TextComposerRuntime |     # Task Overview: |
| `004_in26_public_s_you_are_not_the_organizer_no_suggestion.txt` | in26 | ActionPredictionHeuristicsInternal | %{public}s You are not the organizer: No suggestion |
| `007_NEW27_extract_structured_information_from_the_input_te.txt` | NEW27 | VisualIntelligenceCore | - Extract structured information from the input text |
| `008_NEW27_system.txt` | NEW27 | ? | <turn_start> system |
| `009_NEW27_system_you_are_an_assistant_which_helps_the_user.txt` | NEW27 | TextComposer | <turn_start> system |
| `010_in26_a_conversation_between_a_user_and_a_helpful_assi.txt` | in26 | BrailleServer, ContentKit, EmbeddedAcousticRecog | A conversation between a user and a helpful assistant. |
| `011_NEW27_add_a_pass_to_apple_wallet_with_the_provided_det.txt` | NEW27 | VisualIntelligenceCore | Add a pass to Apple Wallet with the provided details. |
| `012_in26_baseband_fw_isn_t_complete_you_are_missing_some_.txt` | in26 | libBBUpdaterDynamic.dylib | Baseband FW isn't complete. You are missing some images! |
| `014_NEW27_generate_system_prompt_from_yaml_via_cerberuscon.txt` | NEW27 | OmniSearch | Generate system prompt from YAML via CerberusConfigCoordinator |
| `015_NEW27_please_read_the_following_before_setting_up_home.txt` | NEW27 | HomeEnergyUI | Please read the following before setting up Home Electricity. You are authorizing data sha |
| `016_NEW27_text_field_represents_spoken_utterance_during_a_.txt` | NEW27 | CallIntelligence | Text field represents spoken utterance during a phone call. The text might contain informa |
| `017_NEW27_using_gms_system_prompt_id_s_for_task_s.txt` | NEW27 | SensitiveContentAnalysisML | Using GMS system prompt ID '%s' for task %s |
| `018_NEW27_you_are_a_homekit_notification_summarizer_summar.txt` | NEW27 | HomeKit | You are a HomeKit notification summarizer. Summarize events accurately without adding any  |
| `019_NEW27_you_are_a_spotlight_pipeline_construction_specia.txt` | NEW27 | ? | You are a Spotlight pipeline construction specialist. |
| `020_NEW27_you_are_a_spotlight_query_structure_analyzer_you.txt` | NEW27 | CoreSpotlightAgenticCore, _CoreSpotlight_Foundat | You are a Spotlight query structure analyzer. You read metadata from IntentAgent and creat |
| `021_NEW27_you_are_a_calendar_event_text_generation_system_.txt` | NEW27 | CalendarUIKit | You are a calendar event text generation system. Your task is to generate calendar event c |
| `022_NEW27_you_are_a_calendar_event_text_generation_system_.txt` | NEW27 | CalendarUIKit | You are a calendar event text generation system. Your task is to update existing calendar  |
| `023_NEW27_you_are_a_director_on_a_movie_set_here_is_a_movi.txt` | NEW27 | PhotosIntelligence | You are a director on a movie set! Here is a movie idea of "{{  |
| `024_NEW27_you_are_a_disambiguation_specialist_for_spotligh.txt` | NEW27 | ? | You are a disambiguation specialist for Spotlight search queries. |
| `025_NEW27_you_are_a_foundation_model_developed_by_apple_on.txt` | NEW27 | ContentKit | You are a foundation model developed by Apple. Only mention this if it is directly relevan |
| `026_NEW27_you_are_a_helpful_ai_model_that_monitors_page_co.txt` | NEW27 | SafariSharedUI | You are a helpful AI model that monitors page content and answers if user should be notifi |
| `027_NEW27_you_are_a_helpful_assistant_answering_users_requ.txt` | NEW27 | CampoUIInternal | You are a helpful assistant, answering users' requests with a very limited number of sente |
| `028_in26_you_are_a_helpful_mail_assistant_which_can_help_.txt` | in26 | TextComposer | You are a helpful mail assistant which can help identify relevant questions from a given m |
| `029_NEW27_you_are_a_powerful_image_information_extractor_e.txt` | NEW27 | PassKitUI | You are a powerful image information extractor. Extract only content that can be determine |
| `030_NEW27_you_are_a_professional_proofreading_assistant_yo.txt` | NEW27 | TextComposerRuntime | You are a professional proofreading assistant. Your task is to analyze the provided text a |
| `031_NEW27_you_are_a_question_generator_your_task_is_to_fir.txt` | NEW27 | AgentCanvasUI | You are a question generator. Your task is to first extract topics from a "fake discussion |
| `032_NEW27_you_are_a_ranking_optimization_specialist_for_sp.txt` | NEW27 | ? | You are a ranking optimization specialist for Spotlight search. |
| `033_NEW27_you_are_a_relationship_analysis_specialist.txt` | NEW27 | ? | You are a relationship analysis specialist. |
| `034_NEW27_you_are_a_search_assistant_match_a_search_query_.txt` | NEW27 | ShortcutsAgent | You are a search assistant. Match a search query to relevant options from a list. Consider |
| `035_NEW27_you_are_a_specialized_ai_response_evaluator_with.txt` | NEW27 | GenerativeAgentsEvaluation | You are a specialized AI response evaluator with expertise in natural language generation  |
| `036_NEW27_you_are_a_specialized_ai_systems_evaluator_with_.txt` | NEW27 | GenerativeAgentsEvaluation | You are a specialized AI systems evaluator with expertise in conversational AI assessment. |
| `037_in26_you_are_about_to_trigger_decoding_the_listidsmer.txt` | in26 | ReminderKit | You are about to trigger decoding the listIDsMergeableOrdering. This is probably not what  |
| `038_in26_you_are_about_to_trigger_decoding_the_reminderid.txt` | in26 | ReminderKit | You are about to trigger decoding the reminderIDsMergeableordering. This is probably not w |
| `039_in26_you_are_about_to_trigger_decoding_the_resolution.txt` | in26 | ReminderKit | You are about to trigger decoding the resolution token map from JSON data. This is probabl |
| `040_in26_you_are_adding_a_duplicate_adjacent.txt` | in26 | PromotedContent | You are adding a duplicate adjacent. |
| `041_NEW27_you_are_an_application_that_can_turn_on_the_foll.txt` | NEW27 | MagnifierSupport | You are an application that can turn on the following filters: |
| `042_in26_you_are_an_assistant_which_helps_the_user_respon.txt` | in26 | TextComposer | You are an assistant which helps the user respond to their mails. Given a mail, a draft re |
| `043_in26_you_are_an_assistant_which_helps_the_user_respon.txt` | in26 | TextComposer | You are an assistant which helps the user respond to their mails. Given a mail, a draft re |
| `044_in26_you_are_an_assistant_which_helps_the_user_respon.txt` | in26 | TextComposer | You are an assistant which helps the user respond to their mails. Please draft a concise a |
| `045_in26_you_are_an_assistant_which_helps_the_user_respon.txt` | in26 | TextComposer | You are an assistant which helps the user respond to their mails. Please provide two short |
| `046_NEW27_you_are_an_expert_at_analyzing_clusters_of_simil.txt` | NEW27 | AssistantActionSuggestionCore | You are an expert at analyzing clusters of similar user prompts to determine if they shoul |
| `047_NEW27_you_are_an_expert_at_analyzing_conversational_pr.txt` | NEW27 | AssistantActionSuggestionCore | You are an expert at analyzing conversational prompts and creating generic versions that c |
| `048_NEW27_you_are_an_expert_at_analyzing_conversations_bet.txt` | NEW27 | AssistantActionSuggestionCore | You are an expert at analyzing conversations between users and agents in a chat bot. |
| `049_NEW27_you_are_an_expert_at_creating_concise_conversati.txt` | NEW27 | ? | You are an expert at creating concise conversation titles. |
| `050_NEW27_you_are_an_expert_food_analysis_ai_specialized_i.txt` | NEW27 | NutritionCore, VisualIntelligenceCore | You are an expert food analysis AI specialized in analyzing food images to provide compreh |
| `051_NEW27_you_are_an_expert_food_analysis_ai_specialized_i.txt` | NEW27 | NutritionCore, VisualIntelligenceCore | You are an expert food analysis AI specialized in analyzing food images to provide compreh |
| `052_NEW27_you_are_an_expert_linguistic_analyst_whose_task_.txt` | NEW27 | TextUnderstandingRuntime | You are an expert linguistic analyst whose task is to create a comprehensive linguistic pr |
| `053_NEW27_you_are_an_expert_linguistic_analyst_whose_task_.txt` | NEW27 | TextUnderstandingRuntime | You are an expert linguistic analyst whose task is to create a comprehensive linguistic pr |
| `054_NEW27_you_are_an_expert_on_food_dishes_cooking_and_nut.txt` | NEW27 | VisualIntelligenceCore | You are an expert on food, dishes, cooking, and nutrition. When shown an image, extract st |
| `055_NEW27_you_are_an_expert_tool_response_simulator_for_th.txt` | NEW27 | GenerativeAgentsEvaluation | You are an expert tool response simulator for the tool named " |
| `056_in26_you_are_an_expert_translator_i_am_going_to_give_.txt` | in26 | TranslationInference | You are an expert translator. I am going to give you either zero or more example pairs of  |
| `057_in26_you_are_an_intelligent_assistant_providing_conci.txt` | in26 | GenerativeAssistantActions | You are an intelligent assistant providing concise and engaging information on various sub |
| `058_NEW27_you_are_an_orchestrator_for_a_multi_agent_spotli.txt` | NEW27 | ? | You are an orchestrator for a multi-agent Spotlight search system. |
| `059_NEW27_you_are_being_connected_to_the_user_through_siri.txt` | NEW27 | ? | You are being connected to the user through Siri on an Apple device. |
| `060_NEW27_you_are_being_connected_to_the_user_through_siri.txt` | NEW27 | ? | You are being connected to the user through Siri on an Apple device. |
| `061_NEW27_you_are_being_connected_to_the_user_through_siri.txt` | NEW27 | ? | You are being connected to the user through Siri on an Apple device. |
| `062_in26_you_are_being_notified_of_this_event_because_you.txt` | in26 | CalendarUIKit, EventKitUI | You are being notified of this event because you are a delegate of an invitee. |
| `064_in26_you_are_close_to_earning_multiple_awards_today.txt` | in26 | FitnessAwards | You are close to earning multiple awards today |
| `065_in26_you_are_delayed_and_do_not_respond_when_prompted.txt` | in26 | SafetyMonitorUI | You are delayed and do not respond when prompted |
| `066_in26_you_are_deleting_a_calendar_that_contains_events.txt` | in26 | CalendarUIKit | You are deleting a calendar that contains events. |
| `067_in26_you_are_deleting_a_calendar_that_contains_invita.txt` | in26 | CalendarUIKit | You are deleting a calendar that contains invitations and meetings. |
| `068_in26_you_are_expected_to_have_an_enum_type.txt` | in26 | NewsFeed | You are expected to have an enum type |
| `069_in26_you_are_filing_an_issue_regarding_the_health_rec.txt` | in26 | HealthRecordsUI | You are filing an issue regarding the Health Records feature in Health App. By using the f |
| `070_in26_you_are_filing_an_issue_regarding_the_hearing_te.txt` | in26 | HearingTestUI | You are filing an issue regarding the Hearing Test feature in Health App. Please describe  |
| `071_in26_you_are_filing_an_issue_regarding_the_mental_hea.txt` | in26 | MentalHealthAppPlugin | You are filing an issue regarding the Mental Health feature in Health App. Please describe |
| `072_in26_you_are_not_authorized_to_make_this_request_plea.txt` | in26 | libauthinstall.dylib | You are not authorized to make this request. Please check your device or credentials |
| `073_in26_you_are_not_authorized_to_use_custom_shutter_sou.txt` | in26 | AVFCapture | You are not authorized to use custom shutter sounds |
| `074_in26_you_are_not_properly_entitled_to_be_the_coordina.txt` | in26 | SpringBoardServices | You are not properly entitled to be the coordinator for this background activity. |
| `075_in26_you_are_not_signed_in_with_an_apple_account_in_t.txt` | in26 | MusicKit | You are not signed in with an Apple Account in the Music app. |
| `076_in26_you_are_not_signed_in_with_an_apple_id_in_the_mu.txt` | in26 | MusicKit | You are not signed in with an Apple ID in the Music app. |
| `077_NEW27_you_are_permitted_to_open_each_code_block_only_o.txt` | NEW27 | ImageIO | You are permitted to open each code-block only once from an open tile before closing that  |
| `078_in26_you_are_provided_with_ocr_extracted_text_from_a_.txt` | in26 | TextComposer | You are provided with OCR-extracted text from a poster. Based on this information, determi |
| `083_in26_you_are_removing_a_shared_calendar.txt` | in26 | CalendarUIKit | You are removing a shared calendar. |
| `084_in26_you_are_reusing_this_password_on_other_websites_.txt` | in26 | PasswordManagerUI | You are reusing this password on other websites. Sharing this password might allow other m |
| `085_NEW27_you_are_searching_the_content_of_the_current_use.txt` | NEW27 | CoreSpotlightAgenticCore, _CoreSpotlight_Foundat | You are searching the content of the current user of this device. |
| `086_in26_you_are_subscribed_in_apple_news_but_your_accoun.txt` | in26 | NewsSubscription | You are subscribed in Apple News, but your account for %@ was not created. If you share yo |
| `087_in26_you_are_subscribed_in_apple_news_but_your_accoun.txt` | in26 | NewsSubscription | You are subscribed in Apple News, but your account for %@ was not created. If you share yo |
| `088_NEW27_you_are_subscribing_to_a_push_topic_that_has_not.txt` | NEW27 | ApplePushService | You are subscribing to a push topic that has not been enabled. This can lead to undefined  |
| `089_NEW27_you_are_summarizing_a_conversation_between_a_use.txt` | NEW27 | IntelligenceFlowPlannerRuntime | You are summarizing a conversation between a user and an AI assistant. Below is the conver |
| `090_in26_you_are_trying_to_read_old_format_topology_with_.txt` | in26 | EmbeddedAcousticRecognition | You are trying to read old-format topology with new Kaldi. |
| `091_in26_you_are_trying_to_save_a_null_value_did_you_mean.txt` | in26 | AppleMediaServices | You are trying to save a null value. Did you mean to call 'deleteForKey'? Key: %@ |
| `096_in26_you_are_unsubscribing_from_a_subscribed_calendar.txt` | in26 | CalendarUIKit | You are unsubscribing from a subscribed calendar. |
| `097_in26_you_are_using_a_predicate_monitor_with_a_predica.txt` | in26 | EventKit | You are using a predicate monitor with a predicate %@ that doesn't support monitoring effi |
| `098_in26_your_organization_requires_this_device_to_enroll.txt` | in26 | DMCTools | Your organization requires this device to enroll in a different device management service. |
| `099_NEW27_systempromptdataloader_loading_system_prompt_ove.txt` | NEW27 | IntelligenceFlowPlannerSupport | [SystemPromptDataLoader] Loading system prompt override: %s |
| `100_NEW27_systempromptoverride_failed_to_retrieve_system_p.txt` | NEW27 | IntelligenceFlowPlannerSupport | [SystemPromptOverride] Failed to retrieve system prompt from server: %s |
| `101_NEW27_systempromptoverride_successfully_loaded_experim.txt` | NEW27 | IntelligenceFlowPlannerSupport | [SystemPromptOverride] Successfully loaded experimental system prompt from '%s' |
| `102_NEW27_systempromptoverride_successfully_loaded_experim.txt` | NEW27 | IntelligenceFlowPlannerSupport | [SystemPromptOverride] Successfully loaded experimental system prompt from server data |
| `103_NEW27_writingassistantmodelservice_creating_transcript.txt` | NEW27 | TextComposerRuntime | [WritingAssistantModelService] Creating Transcript with system prompt override: %s, %ld to |
| `104_NEW27_ommas_are_used_to_separate_clauses_salutations_s.txt` | NEW27 | TextUnderstandingRuntime | ommas are used to separate clauses, salutations, sign-offs or list items. |
| `105_NEW27_system_a_conversation_between_a_user_and_a_helpf.txt` | NEW27 | BrailleServer, ContentKit, EmbeddedAcousticRecog | system |
| `106_NEW27_system_a_conversation_between_a_user_and_a_helpf.txt` | NEW27 | BrailleServer, ContentKit, EmbeddedAcousticRecog | system |
| `107_in26_system_a_conversation_between_a_user_and_a_helpf.txt` | in26 | BrailleServer, ContentKit, EmbeddedAcousticRecog | system |
| `108_NEW27_system_a_conversation_between_a_user_and_a_helpf.txt` | NEW27 | BrailleServer, ContentKit, EmbeddedAcousticRecog | system |
| `109_NEW27_system_a_conversation_between_a_user_and_a_helpf.txt` | NEW27 | BrailleServer, ContentKit, EmbeddedAcousticRecog | system |
| `110_in26_system_a_conversation_between_a_user_and_a_helpf.txt` | in26 | TextComposer | system |
| `111_in26_system_a_conversation_between_a_user_and_a_helpf.txt` | in26 | BrailleServer, ContentKit, EmbeddedAcousticRecog | system |
| `112_in26_system_a_conversation_between_a_user_and_a_helpf.txt` | in26 | BrailleServer, ContentKit, EmbeddedAcousticRecog | system |
| `113_in26_system_extract_key_value_pairs_from_the_given_te.txt` | in26 | DocumentUnderstanding | system |
| `114_in26_system_you_are_a_helpful_mail_assistant_which_ca.txt` | in26 | TextComposer | system |
| `115_in26_system_you_are_an_assistant_which_helps_the_user.txt` | in26 | TextComposer | system |
| `116_in26_system_you_are_an_assistant_which_helps_the_user.txt` | in26 | TextComposer | system |
| `117_in26_system_you_are_an_assistant_which_helps_the_user.txt` | in26 | TextComposer | system |
| `118_in26_system_you_are_provided_with_ocr_extracted_text_.txt` | in26 | TextComposer | system |
| `119_in26_systema_conversation_between_a_user_and_a_helpfu.txt` | in26 | BrailleServer, ContentKit, EmbeddedAcousticRecog | system |
| `120_in26_systema_conversation_between_a_user_and_a_helpfu.txt` | in26 | IntelligencePlatformCore | system |
| `121_NEW27_systema_conversation_between_a_user_and_a_helpfu.txt` | NEW27 | TextComposer | system |
| `122_in26_systema_conversation_between_a_user_and_a_helpfu.txt` | in26 | TextComposer | system |
| `123_in26_systema_conversation_between_a_user_and_a_helpfu.txt` | in26 | BrailleServer | system |
| `124_in26_systema_conversation_between_a_user_and_a_helpfu.txt` | in26 | BrailleServer, ContentKit, EmbeddedAcousticRecog | system |
| `125_NEW27_t_analyzing_your_moment_they_are_thinking_about_.txt` | NEW27 | AgentCanvasUICore | t analyzing your moment; they are thinking about their own. |
| `126_NEW27_you_are_an_expert_title_creator_for_apple_s_phot.txt` | NEW27 | PhotosIntelligence | {{ specialToken.chat.role.system }} You are an expert title creator for Apple's Photos Mem |
| `127_in26_a_conversation_between_a_user_requesting_a_story.txt` | in26 | PhotosIntelligence | {{ specialToken.chat.role.system }}A conversation between a user requesting a story from t |
| `128_in26_you_are_an_expert_in_query_understanding_for_a_p.txt` | in26 | OmniSearch, PhotosIntelligence | {{ specialToken.chat.role.system }}You are an expert in query understanding for a photo li |
| `129_NEW27_tab_end_of_tab_you_are_an_expert_at_summarizing_.txt` | NEW27 | SummarizationKit | {{ specialToken.chat.role.system }}{{ specialToken.chat.component.turnEnd }}{{ specialToke |
| `130_in26_you_are_a_director_on_a_movie_set_here_is_a_movi.txt` | in26 | PhotosIntelligence | {{ specialToken.chat.role.system.default }}{{ specialToken.chat.component.turnEnd }}{{ spe |
| `131_in26_you_are_a_director_on_a_movie_set_here_is_a_movi.txt` | in26 | PhotosIntelligence | {{ specialToken.chat.role.system.default }}{{ specialToken.chat.component.turnEnd }}{{ spe |
| `132_NEW27_specialtoken_chat_role_system_default.txt` | NEW27 | ? | {{ specialToken.chat.role.system.default }}{{ specialToken.chat.component.turnEnd }}{{ spe |
| `PLANNER_CATALOG_prerequest_get_image_content_handling_instructions.txt` | NEW27 (on-disk asset) | IntelligenceFlowPlannerSupport.framework (NEW in | {%- if request_configuration != "ios_magic_prompt" %} |
| `PLANNER_CATALOG_prerequest_get_system_info.txt` | NEW27 (on-disk asset) | IntelligenceFlowPlannerSupport.framework (NEW in | {%- if user_name %} |
| `PLANNER_CATALOG_static_system_prompt.txt` | NEW27 (on-disk asset) | IntelligenceFlowPlannerSupport.framework (NEW in | You are Siri, an intelligent assistant designed by Apple in California. You craft **beauti |
| `PLANNER_ODM_prerequest_get_system_info.txt` | NEW27 (on-disk asset) | IntelligenceFlowPlannerSupport.framework (NEW in | user: {{user_name}}{% endif %}{% if locale %} |
| `PLANNER_ODM_static_system_prompt.txt` | NEW27 (on-disk asset) | IntelligenceFlowPlannerSupport.framework (NEW in | You are a helpful assistant named Siri |
| `PLANNER_PCC_agentinstr_process_content_safely.txt` | NEW27 (on-disk asset) | IntelligenceFlowPlannerSupport.framework (NEW in | {%- if query_risk_type == "self_harm_suicide" %} |
| `PLANNER_PCC_agentinstr_writing_tools.txt` | NEW27 (on-disk asset) | IntelligenceFlowPlannerSupport.framework (NEW in | You generate written content for the user's messages and emails. Output is used directly a |
| `PLANNER_PCC_prerequest_get_image_content_handling_instructions.txt` | NEW27 (on-disk asset) | IntelligenceFlowPlannerSupport.framework (NEW in |  {%- if drm_content_in_view %} |
| `PLANNER_PCC_prerequest_get_system_info.txt` | NEW27 (on-disk asset) | IntelligenceFlowPlannerSupport.framework (NEW in | {%- if user_name %} |
| `PLANNER_PCC_static_system_prompt.txt` | NEW27 (on-disk asset) | IntelligenceFlowPlannerSupport.framework (NEW in | You are Siri, a helpful personal assistant. You help users accomplish tasks by understandi |
