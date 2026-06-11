### Hi, I'm Sarthak

I build ML tooling and contribute to open-source Python libraries in time-series forecasting, model interpretability, and data engineering.

**Open source contributions**

*Active:*
- [Kuadrant/mcp-gateway#925](https://github.com/Kuadrant/mcp-gateway/pull/925) — `fix(mcp-router)` make `ExtProcServer.RoutingConfig` swap race-free with `atomic.Pointer` `open`
- meshery/meshery — `utils.IsClosed` cleanup chain in `server/models`: [#19572](https://github.com/meshery/meshery/pull/19572) `[server]` fix `Broadcast` races + value-copy clobber + tests, [#19580](https://github.com/meshery/meshery/pull/19580) replace remaining `IsClosed` gates with non-blocking sends, [#19585](https://github.com/meshery/meshery/pull/19585) remove the helper itself, [#19643](https://github.com/meshery/meshery/pull/19643) init subscriber slices with `len=0` `4 PRs open`
- [hyperledger-cello/cello#788](https://github.com/hyperledger-cello/cello/pull/788) — ci: bump CI to Python 3.11 and refresh deprecated GitHub Actions `open`
- [kagent-dev/kagent#1786](https://github.com/kagent-dev/kagent/pull/1786) — fix(skills-init): install openssh-client so ssh-keyscan is available `open`
- [aaif-goose/goose#9473](https://github.com/aaif-goose/goose/pull/9473) — feat(server): paginate messages in GET /sessions/{session_id} (limit + offset, openapi + TS client regen) `open`
- [ag2ai/faststream#2874](https://github.com/ag2ai/faststream/pull/2874) — fix(cli): surface YAML and AsyncAPI errors from `docs serve` (Sehat1137-invited redo of #2858) `open`
- [aaif-goose/goose#9289](https://github.com/aaif-goose/goose/pull/9289) — fix(desktop): reuse existing window for recipe deep links `open`
- [jcrist/msgspec#1028](https://github.com/jcrist/msgspec/pull/1028) — place null last in anyOf for optional unions in JSON schema `open`
- [modelcontextprotocol/inspector#1295](https://github.com/modelcontextprotocol/inspector/pull/1295) — fix(client): fully collapse Output Schema and Meta panels in ToolsTab `open`
- [modelcontextprotocol/inspector#1296](https://github.com/modelcontextprotocol/inspector/pull/1296) — fix(server): redact sensitive env vars and headers from connection logs `open`
- [OpenHands/OpenHands#14307](https://github.com/OpenHands/OpenHands/pull/14307) — fix(frontend): use onSelectionChange for Language dropdown dirty-flag `open`
- [dbt-labs/dbt-core#12815](https://github.com/dbt-labs/dbt-core/pull/12815) — warn when load_result returns None during parse phase `open`
- [DalgoT4D/webapp#1705](https://github.com/DalgoT4D/webapp/pull/1705) — fix: drop empty reader_options from source config `open`
- [sktime/sktime-mcp#114](https://github.com/sktime/sktime-mcp/pull/114) — seasonality detection + structural break diagnostics for sktime's MCP layer `open`
- [sktime/sktime-mcp#347](https://github.com/sktime/sktime-mcp/pull/347) — map NaN/Inf to null in `sanitize_for_json` to keep tool responses JSON-safe `open`
- [sktime/sktime#9876](https://github.com/sktime/sktime/issues/9876) — proposed MCP-native agentic estimator for forecasting pipeline selection `open`
- [sktime/sktime#9846](https://github.com/sktime/sktime/issues/9846) — proposed agentic model selection benchmark `open`
- shap/shap — type-annotation migration for [#3730](https://github.com/shap/shap/issues/3730) (`check_untyped_defs`): [#4445](https://github.com/shap/shap/pull/4445) `tf_utils` with `TFModel` Protocol, [#4760](https://github.com/shap/shap/pull/4760) `plots/_force`, [#4761](https://github.com/shap/shap/pull/4761) `maskers/_image`, [#4772](https://github.com/shap/shap/pull/4772) `plots/_force_matplotlib` `4 PRs open`
- [pgmpy/pgmpy#2225](https://github.com/pgmpy/pgmpy/pull/2225) — timeseries conversion utilities bridging pgmpy ↔ sktime `open`
- [DalgoT4D/DDP_backend#1037](https://github.com/DalgoT4D/DDP_backend/pull/1037) — Airbyte integration test suite `open`
- [PlanetRead/Video-Watch-Timer#6](https://github.com/PlanetRead/Video-Watch-Timer/pull/6) — dark mode theme support `open`
- [myhealthconnectsociety/project-healthcare#178](https://github.com/myhealthconnectsociety/project-healthcare/pull/178) — interface protocol fix (C4GT) `open`

*Merged / adopted:*
- [vllm-project/aibrix#2296](https://github.com/vllm-project/aibrix/pull/2296) — fix(runtime): validate `lora_name` in `ArtifactDelegationService` to prevent path traversal in artifact loader (merged 2026-06-09 by Jeffwan) `merged`
- [Kuadrant/mcp-gateway#924](https://github.com/Kuadrant/mcp-gateway/pull/924) — `fix(session)` bound `JWTManager.Terminate` cache deletion with a 5s timeout (merged 2026-06-11 by jasonmadigan) `merged`
- [kagent-dev/kagent#1791](https://github.com/kagent-dev/kagent/pull/1791) — fix(controller): return error instead of panicking on unknown auth mode `merged`
- [pepperoni21/ollama-rs#336](https://github.com/pepperoni21/ollama-rs/pull/336) — feat: add OllamaBuilder; deprecate host+port constructors `merged`
- [pepperoni21/ollama-rs#337](https://github.com/pepperoni21/ollama-rs/pull/337) — Relax Tool::call future bound to Send `merged`
- [sktime/sktime-mcp#273](https://github.com/sktime/sktime-mcp/pull/273) — cap MCP data-handle accumulation with LRU eviction (fixes #191) `merged`
- [kagent-dev/kagent#1814](https://github.com/kagent-dev/kagent/pull/1814) — fix(cli): correct MCP secrets sync apply behavior and thread cobra ctx `merged`
- [kagent-dev/kagent#1787](https://github.com/kagent-dev/kagent/pull/1787) — fix(app): wire signal-aware context through controller startup `merged`
- [shap/shap#4436](https://github.com/shap/shap/pull/4436) — type annotations for `_random` (first step of [#3730](https://github.com/shap/shap/issues/3730) `check_untyped_defs` migration) `merged`
- [shap/shap#4480](https://github.com/shap/shap/issues/4480) — filed: `type(x) is tuple` anti-pattern in gradient/deep explainers and partial_dependence (fixed via @neha222222's PR #4508, merged May 27) `fix adopted in maintainer-merged PR`
- [python-poetry/poetry#10908](https://github.com/python-poetry/poetry/pull/10908) — fix(add): include pyproject.toml path in "already present" message `merged`
- [python-poetry/poetry#10909](https://github.com/python-poetry/poetry/pull/10909) — fix(init): validate version constraint in interactive prompt `merged`
- [ag2ai/ag2#2872](https://github.com/ag2ai/ag2/pull/2872) — docs: add Gemini and Azure OpenAI tabs to Quick Start `merged`
- [aaif-goose/goose#9123](https://github.com/aaif-goose/goose/pull/9123) — fix: omit max_tokens for OpenAI-compatible requests when unset `merged`
- [PrefectHQ/fastmcp#4118](https://github.com/PrefectHQ/fastmcp/pull/4118) — fix(http): terminate active streamable-HTTP transports before lifespan shutdown `merged`
- [ag2ai/ag2#2794](https://github.com/ag2ai/ag2/pull/2794) — fix: align optional-extras pins so uv sync resolves `merged`
- [PrefectHQ/fastmcp#4101](https://github.com/PrefectHQ/fastmcp/pull/4101) — fix(tool_transform): hoist $defs to schema root when ArgTransform introduces them `merged`
- [PrefectHQ/fastmcp#4100](https://github.com/PrefectHQ/fastmcp/pull/4100) — fix(auth): silence authlib.jose DeprecationWarning at JWT import `merged`
- [ag2ai/ag2#2782](https://github.com/ag2ai/ag2/pull/2782) — Fix LLMConfig for 5 notebooks (6th in the migration series) `merged`
- [aaif-goose/goose#9035](https://github.com/aaif-goose/goose/pull/9035) — fix(openai): accept null tool_call arguments in streaming chunks `merged`
- [GitoxideLabs/gitoxide#2607](https://github.com/GitoxideLabs/gitoxide/pull/2607) — gix-command: pass shell name (not `--`) as `$0` to `<shell> -c` `merged`
- [GitoxideLabs/gitoxide#2575](https://github.com/GitoxideLabs/gitoxide/pull/2575) — document why each fixture archive is .gitignored `merged`
- [python-poetry/poetry#10835](https://github.com/python-poetry/poetry/pull/10835) — docs: VCS ignore interaction with packages config `merged`
- [tattle-made/feluda#588](https://github.com/tattle-made/feluda/pull/588) — UMAP dimension reduction `merged`
- [tattle-made/feluda#589](https://github.com/tattle-made/feluda/pull/589) — unit tests for core operator `merged`
- [Noethys/Noethys#84](https://github.com/Noethys/Noethys/pull/84) — SQL injection vulnerability fix `fixes adopted manually`
- [0xPlaygrounds/rig#1556](https://github.com/0xPlaygrounds/rig/issues/1556) — Chat trait `&mut Vec<Message>` round-trip (issue closed by maintainer's #1733) `fix adopted in maintainer's PR`

*Past contributions:*
- [Kuadrant/mcp-gateway#923](https://github.com/Kuadrant/mcp-gateway/pull/923) — `fix(broker)` take `RLock` in `findServerByName` and use `MCPName()` in log; closed 2026-06-11 because Aman-Cool's parallel fix had already landed on `main`. Same root cause; hardening direction acknowledged.
- [kagent-dev/kagent#1825](https://github.com/kagent-dev/kagent/pull/1825) — test(migrations): add data-preserving upgrade test for workload_type backfill `closed-stale by github-actions after 20 days inactivity`
- [GitoxideLabs/gitoxide#2606](https://github.com/GitoxideLabs/gitoxide/pull/2606) — gix-url: accept `impl Into<&BStr>` in `parse` `closed by author — signature widening broke 34 downstream .into() callers; awaiting maintainer guidance on preferred shape`
- [PrefectHQ/fastmcp#4172](https://github.com/PrefectHQ/fastmcp/pull/4172) — wrap pydantic ValidationError as fastmcp ValidationError `closed by maintainer — discussion-on-issue required first`
- [PrefectHQ/fastmcp#4171](https://github.com/PrefectHQ/fastmcp/pull/4171) — event_store concurrent eviction guard `closed by maintainer — preferred fix is upstream in py-key-value-aio`
- [ag2ai/faststream#2858](https://github.com/ag2ai/faststream/pull/2858) — feat(cli): pluggable yaml parser for docs serve `closed by maintainer — over-scoped (see #2874 redo)`
- [ag2ai/faststream#2864](https://github.com/ag2ai/faststream/pull/2864) — re-export BrokerUsecase from top-level package `closed by maintainer`
- [hynek/structlog#810](https://github.com/hynek/structlog/pull/810) — LogRecord.args timing in ProcessorFormatter `closed — supported path is pass_foreign_args=True`
- [avantifellows/portal-backend#73](https://github.com/avantifellows/portal-backend/pull/73) — fix create-access-token route bug `closed — not reviewed`
- [proteanhq/protean#504](https://github.com/proteanhq/protean/pull/504) — FastAPI server integration `closed — superseded by maintainer's version`

**Get in touch:** sarthak.bhardwaj21b@iiitg.ac.in
