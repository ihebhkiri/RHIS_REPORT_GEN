# Graph Report - RHIS  (2026-08-21)

## Corpus Check
- 236 files · ~88,291 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 1871 nodes · 4210 edges · 105 communities (83 shown, 22 thin omitted)
- Extraction: 93% EXTRACTED · 7% INFERRED · 0% AMBIGUOUS · INFERRED: 278 edges (avg confidence: 0.8)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- org.springframework.data.jpa.repository.JpaRepository
- lombok.RequiredArgsConstructor
- DataSetFieldType
- ExportComponent
- ReportJobProperties
- org.junit.jupiter.api.Test
- UserPrincipal
- Components
- ReportSnapshotReader
- FilterEditorComponent
- DataSetField
- ReportGenerationEntity
- ReportSqlBuilder
- Dataset
- Administration des données du Report Builder — spécification Figma
- PdfReportExportWriter
- UserService
- ReportSnapshotStorageTest
- ReportExportWriterTest
- ReportPreviewPostgresIntegrationTest.java
- ReportJobCleanupService
- org.springframework.transaction.annotation.Transactional
- DataSetFieldResponse
- TableRelationProjection
- dependencies
- devDependencies
- ReportField
- configuration.component.ts
- ConfigurationComponent
- RHIS — génération asynchrone et export temporaire des rapports
- org.springframework.stereotype.Service
- SecurityConfig.java
- UserEntity
- DataSetEntity
- Administration des tables et champs — spécification UI/UX
- sort-editor.component.ts
- XlsxReportExportWriter
- auth.service.ts
- Refactoring KISS du workflow Export front et back
- DataSetInitializer
- AuthServiceImpl.java
- ReportExportWorkerTest
- RapportsComponent
- RHIS — simplification du parcours de configuration des rapports
- ReportSnapshotMetadata
- ReportExportService
- Refactoring ciblé de la page Export
- org.springframework.http.ResponseEntity
- ReportGenerationController
- 02 — Définition du rapport : fields, filters, sorts et brouillon local
- options
- 04 — Génération complète asynchrone
- 05 — Export PDF/XLSX et téléchargement
- Rapport d'avancement — Projet RHIS
- Rhis_report_gen
- mvnw
- 01 — Sélection des datasets et chargement de la configuration
- build
- @schematics/angular:component
- package.json
- ReportConfigurationLoader
- 06 — Authentification par cookies et refresh token
- development
- scripts
- architect
- RhisApplication
- ResolvedReportDefinition
- ReportRelatedCardComponent
- IhebComponent
- InvalidTokenException
- PasswordMismatchException
- TokenExpiredException
- flows/README.md
- 03 — Preview synchrone du rapport
- Correction ciblée du layout de la page Export
- karma-chrome-launcher
- Global Constraints
- ForgotPasswordRequest.java
- ResetPasswordRequest.java
- CreateUserResponse.java
- UserResponse.java
- RHIS.com:RHIS
- ReportGenerationService
- Report export vertical stepper design
- File Map
- Global Constraints
- Global Constraints
- RhisReportGen
- RHIS — documentation ciblée du flux de rapports
- Étapes détaillées
- Global Constraints
- XLSX Temporal Snapshot Compatibility Design
- .write
- Global Constraints
- Global Constraints
- Global Constraints
- Global Constraints
- Login détaillé
- Independent report formats with PrimeNG implementation plan
- Heuristique	Exemple
- @angular/platform-browser
- @angular/router
- primeicons
- @types/jasmine
- typescript

## God Nodes (most connected - your core abstractions)
1. `DataSetField` - 46 edges
2. `ReportJobProperties` - 41 edges
3. `DataSetEntity` - 39 edges
4. `ReportPreviewRequest` - 37 edges
5. `ExportComponent` - 36 edges
6. `UserEntity` - 36 edges
7. `FilterEditorComponent` - 33 edges
8. `DataSetFieldType` - 33 edges
9. `UserRepository` - 29 edges
10. `ReportGenerationEntity` - 28 edges

## Surprising Connections (you probably didn't know these)
- `ReportPreviewColumn` --references--> `DatasetFieldType`  [EXTRACTED]
  Frontend/Rhis_report_gen/src/app/features/rapports/models/report-preview.model.ts → Frontend/Rhis_report_gen/src/app/features/rapports/models/dataset-field.model.ts
- `OperatorOption` --references--> `FilterOperator`  [EXTRACTED]
  Frontend/Rhis_report_gen/src/app/features/rapports/pages/configuration/components/filter-editor/filter-editor.component.ts → Frontend/Rhis_report_gen/src/app/features/rapports/models/dataset-field.model.ts
- `ReportField` --inherits--> `DatasetField`  [EXTRACTED]
  Frontend/Rhis_report_gen/src/app/features/rapports/pages/configuration/configuration.models.ts → Frontend/Rhis_report_gen/src/app/features/rapports/models/dataset-field.model.ts
- `SelectedDataset` --inherits--> `Dataset`  [EXTRACTED]
  Frontend/Rhis_report_gen/src/app/features/rapports/pages/configuration/configuration.models.ts → Frontend/Rhis_report_gen/src/app/features/rapports/models/dataset.model.ts
- `DatasetAccordionView` --references--> `Dataset`  [EXTRACTED]
  Frontend/Rhis_report_gen/src/app/features/rapports/pages/source_de_donnes/rapports.component.ts → Frontend/Rhis_report_gen/src/app/features/rapports/models/dataset.model.ts

## Import Cycles
- None detected.

## Communities (105 total, 22 thin omitted)

### Community 0 - "org.springframework.data.jpa.repository.JpaRepository"
Cohesion: 0.06
Nodes (38): jakarta.persistence.Entity, jakarta.persistence.MappedSuperclass, jakarta.persistence.PrePersist, jakarta.persistence.Table, lombok.Getter, lombok.NoArgsConstructor, org.springframework.context.annotation.Profile, org.springframework.core.annotation.Order (+30 more)

### Community 1 - "lombok.RequiredArgsConstructor"
Cohesion: 0.09
Nodes (24): InputStreamResource, lombok.RequiredArgsConstructor, org.springframework.core.io.InputStreamResource, org.springframework.security.core.GrantedAuthority, org.springframework.web.bind.annotation.DeleteMapping, org.springframework.web.bind.annotation.GetMapping, org.springframework.web.bind.annotation.PutMapping, org.springframework.web.bind.annotation.RequestMapping (+16 more)

### Community 2 - "DataSetFieldType"
Cohesion: 0.07
Nodes (28): org.junit.jupiter.api.BeforeEach, org.junit.jupiter.api.extension.ExtendWith, org.mockito.junit.jupiter.MockitoExtension, DataSetFieldType, BOOLEAN, DATE, DATE_TIME, DECIMAL (+20 more)

### Community 3 - "ExportComponent"
Cohesion: 0.07
Nodes (22): ReportDraft, ReportExport, ReportExportFormat, ReportExportStatus, ReportGeneration, ReportGenerationPhase, ReportGenerationStatus, ApiProblem (+14 more)

### Community 4 - "ReportJobProperties"
Cohesion: 0.19
Nodes (7): org.springframework.boot.context.properties.ConfigurationProperties, ReportJobProperties, FileSystemReportArtifactStorage, Override, StorageDeleteException, ArtifactWriter, FunctionalInterface

### Community 5 - "org.junit.jupiter.api.Test"
Cohesion: 0.06
Nodes (34): Connection, java.sql.PreparedStatement, java.sql.ResultSet, org.junit.jupiter.api.Test, org.springframework.boot.test.context.SpringBootTest, org.springframework.boot.webmvc.test.autoconfigure.WebMvcTest, org.springframework.context.annotation.Import, org.springframework.jdbc.core.JdbcTemplate (+26 more)

### Community 6 - "UserPrincipal"
Cohesion: 0.10
Nodes (13): org.springframework.http.ResponseCookie, AuthController, GetMapping, PostMapping, RequestMapping, RestController, LoginRequest, LoginResponse (+5 more)

### Community 7 - "Components"
Cohesion: 0.05
Nodes (37): Agent Prompt Guide, Badge — Outline, Badge — Soft, Badge — Solid, Border Radius, Breadcrumb Trail, Card, Components (+29 more)

### Community 8 - "ReportSnapshotReader"
Cohesion: 0.25
Nodes (4): com.fasterxml.jackson.core.type.TypeReference, com.fasterxml.jackson.databind.ObjectMapper, com.lowagie.text.pdf.PdfReader, ReportSnapshotReader

### Community 9 - "FilterEditorComponent"
Cohesion: 0.14
Nodes (4): DatasetFieldType, ReportPreviewColumn, FilterEditorComponent, Component

### Community 10 - "DataSetField"
Cohesion: 0.17
Nodes (6): DataSetField, Entity, Table, ReportResourceNotFoundException, ReportValidationException, ReportDefinitionResolver

### Community 11 - "ReportGenerationEntity"
Cohesion: 0.13
Nodes (16): org.springframework.data.jpa.repository.Lock, Entity, Table, ReportGenerationEntity, ReportGenerationPhase, COUNTING, FINALIZING, READING_ROWS (+8 more)

### Community 13 - "Dataset"
Cohesion: 0.17
Nodes (11): DatasetField, Dataset, TableRelation, DatasetSelectionResult, DATASET_ICONS, DatasetAccordionView, RelatedDatasetAccumulator, RelatedDatasetView (+3 more)

### Community 14 - "Administration des données du Report Builder — spécification Figma"
Cohesion: 0.06
Nodes (34): `01 — Dataset active`, `02 — Dataset inactive`, `03 — Search & filters`, `04 — Unsaved changes`, `05 — Save feedback`, 10. Frames Figma attendues, 11. Composants Figma, 12. Design system et iconographie (+26 more)

### Community 15 - "PdfReportExportWriter"
Cohesion: 0.11
Nodes (10): java.util.function.IntConsumer, net.sf.jasperreports.engine.JasperPrint, net.sf.jasperreports.engine.JRDataSource, net.sf.jasperreports.engine.JRField, Override, PdfReportExportWriter, SnapshotDataSource, ReportExportWriter (+2 more)

### Community 16 - "UserService"
Cohesion: 0.08
Nodes (16): org.springframework.security.access.prepost.PreAuthorize, PatchMapping, RoleRepository, BulkStatusRequest, CreateUserRequest, UpdateUserRequest, UserDataResponse, UserStatsResponse (+8 more)

### Community 17 - "ReportSnapshotStorageTest"
Cohesion: 0.19
Nodes (6): java.io.FilterInputStream, ObjectMapper, SnapshotConsumer, CloseTrackingInputStream, Override, ReportSnapshotStorageTest

### Community 18 - "ReportExportWriterTest"
Cohesion: 0.17
Nodes (8): PdfReader, Column, ReportSnapshotWriter, CloseTrackingOutputStream, FunctionalInterface, Override, ReportExportWriterTest, ThrowingRunnable

### Community 19 - "ReportPreviewPostgresIntegrationTest.java"
Cohesion: 0.14
Nodes (15): lombok.Setter, org.springframework.scheduling.annotation.Scheduled, ReportExportResponse, Entity, Table, ReportExportEntity, ReportExportFormat, PDF (+7 more)

### Community 21 - "org.springframework.transaction.annotation.Transactional"
Cohesion: 0.12
Nodes (12): org.slf4j.Logger, org.springframework.core.task.TaskExecutor, org.springframework.stereotype.Component, org.springframework.transaction.annotation.Transactional, InProcessReportJobDispatcher, Override, ReportExportWorker, ReportFullQueryExecutor (+4 more)

### Community 22 - "DataSetFieldResponse"
Cohesion: 0.10
Nodes (10): DataSetController, GetMapping, PutMapping, RequestMapping, RestController, DataSetFieldResponse, JoinInfoProjection, TableRelationResponse (+2 more)

### Community 23 - "TableRelationProjection"
Cohesion: 0.12
Nodes (3): TableRelationProjection, Override, TestTableRelation

### Community 24 - "dependencies"
Cohesion: 0.09
Nodes (23): @angular/animations, @angular/cdk, @angular/common, @angular/compiler, @angular/core, @angular/forms, dependencies, @angular/animations (+15 more)

### Community 25 - "devDependencies"
Cohesion: 0.09
Nodes (23): @angular/build, @angular/cli, @angular/compiler-cli, devDependencies, @angular/build, @angular/cli, @angular/compiler-cli, jasmine-core (+15 more)

### Community 26 - "ReportField"
Cohesion: 0.14
Nodes (13): FilterOperator, ReportFilterRequest, ColumnSelectorComponent, Component, FilterEditorState, FilterFieldOption, FilterFieldOptionGroup, FilterRowForm (+5 more)

### Community 27 - "configuration.component.ts"
Cohesion: 0.15
Nodes (13): ReportPreviewCell, ReportPreviewRequest, ReportPreviewResponse, ReportPreviewRow, ReportSortRequest, PreviewDialogComponent, Component, ReportStep (+5 more)

### Community 28 - "ConfigurationComponent"
Cohesion: 0.16
Nodes (3): ConfigurationComponent, Component, ReportConfigurationLoadResult

### Community 29 - "RHIS — génération asynchrone et export temporaire des rapports"
Cohesion: 0.07
Nodes (29): 10. Sécurité et erreurs, 11. Frontend Angular, 12. Tests et critères d’acceptation, 13. Hors périmètre, 14. Ordre de réalisation recommandé, 1. Objectif, 2. Principes retenus, 3.1 Depuis Configuration (+21 more)

### Community 30 - "org.springframework.stereotype.Service"
Cohesion: 0.12
Nodes (17): io.jsonwebtoken.Claims, jakarta.servlet.FilterChain, jakarta.servlet.http.HttpServletRequest, jakarta.servlet.http.HttpServletResponse, javax.crypto.SecretKey, org.springframework.security.core.userdetails.UserDetails, org.springframework.security.core.userdetails.UserDetailsService, org.springframework.stereotype.Service (+9 more)

### Community 31 - "SecurityConfig.java"
Cohesion: 0.18
Nodes (14): org.springframework.boot.context.properties.EnableConfigurationProperties, org.springframework.context.annotation.Bean, org.springframework.context.annotation.Configuration, org.springframework.scheduling.annotation.EnableAsync, org.springframework.security.authentication.AuthenticationManager, org.springframework.security.config.annotation.authentication.configuration.AuthenticationConfiguration, org.springframework.security.config.annotation.method.configuration.EnableMethodSecurity, org.springframework.security.config.annotation.web.builders.HttpSecurity (+6 more)

### Community 32 - "UserEntity"
Cohesion: 0.19
Nodes (11): jakarta.persistence.EntityListeners, org.springframework.data.domain.Page, org.springframework.data.domain.Pageable, org.springframework.data.jpa.domain.support.AuditingEntityListener, Entity, Getter, Setter, Table (+3 more)

### Community 33 - "DataSetEntity"
Cohesion: 0.15
Nodes (11): org.springframework.data.jpa.repository.EntityGraph, org.springframework.data.jpa.repository.Query, DataSetMapper, DataSetResponse, DataSetEntity, Entity, Table, DataSetFieldRepository (+3 more)

### Community 34 - "Administration des tables et champs — spécification UI/UX"
Cohesion: 0.07
Nodes (28): 10. Données mockées, 11. Direction visuelle, 12. Responsive, 13. Accessibilité visuelle, 14. Hors périmètre, 15. Critères d’acceptation, 16. Interfaces publiques, 1. Objectif (+20 more)

### Community 35 - "sort-editor.component.ts"
Cohesion: 0.15
Nodes (7): SortDirection, SORT_DIRECTION_OPTIONS, SortDirectionOption, SortEditorComponent, SortFieldOption, SortFieldOptionGroup, Component

### Community 36 - "XlsxReportExportWriter"
Cohesion: 0.24
Nodes (5): Cell, CellStyle, Override, XlsxReportExportWriter, Workbook

### Community 37 - "auth.service.ts"
Cohesion: 0.13
Nodes (11): App, appConfig, RhisPreset, routes, Component, LoginCredentials, LoginComponent, Component (+3 more)

### Community 38 - "Refactoring KISS du workflow Export front et back"
Cohesion: 0.07
Nodes (27): 10. Validation, 11. Risques, 12. Critère de fin, 1. Objectif, 2. Périmètre, 3. État actuel vérifié, 4.1 Reprise réseau du polling frontend, 4.2 Authentification backend (+19 more)

### Community 39 - "DataSetInitializer"
Cohesion: 0.24
Nodes (6): lombok.extern.slf4j.Slf4j, org.springframework.boot.ApplicationArguments, org.springframework.boot.ApplicationRunner, ColumnInfo, DataSetInitializer, Override

### Community 40 - "AuthServiceImpl.java"
Cohesion: 0.08
Nodes (15): AllArgsConstructor, Builder, Entity, Getter, NoArgsConstructor, Setter, Table, RefreshTokenEntity (+7 more)

### Community 43 - "RHIS — simplification du parcours de configuration des rapports"
Cohesion: 0.10
Nodes (20): 10. Impact backend, 1. Présentation des colonnes, 2. Champs filtrables, 3. Opérateurs visibles, 4. Valeurs temporelles PrimeNG, 5. Page de configuration, 6. Page source de données, 7. Flux d’état (+12 more)

### Community 44 - "ReportSnapshotMetadata"
Cohesion: 0.29
Nodes (5): net.sf.jasperreports.engine.design.JasperDesign, JasperDynamicTableConfigurer, ReportSnapshotMetadata, JasperDynamicTableConfigurerTest, JasperDesign

### Community 45 - "ReportExportService"
Cohesion: 0.28
Nodes (3): ReportConflictException, DownloadPayload, ReportExportService

### Community 46 - "Refactoring ciblé de la page Export"
Cohesion: 0.10
Nodes (19): Changements explicitement rejetés, Design validé, Diagnostic, Mutualisation RxJS, Naming ciblé, Nettoyage SCSS, Objectif, Ordre d’implémentation et risques (+11 more)

### Community 47 - "org.springframework.http.ResponseEntity"
Cohesion: 0.28
Nodes (9): org.springframework.http.converter.HttpMessageNotReadableException, org.springframework.http.HttpStatus, org.springframework.http.ProblemDetail, org.springframework.http.ResponseEntity, org.springframework.web.bind.annotation.ExceptionHandler, org.springframework.web.bind.annotation.RestControllerAdvice, org.springframework.web.bind.MethodArgumentNotValidException, ReportExceptionHandler (+1 more)

### Community 48 - "ReportGenerationController"
Cohesion: 0.19
Nodes (7): CreateReportExportRequest, DeleteMapping, GetMapping, PostMapping, RequestMapping, RestController, ReportGenerationController

### Community 49 - "02 — Définition du rapport : fields, filters, sorts et brouillon local"
Cohesion: 0.11
Nodes (18): 02 — Définition du rapport : fields, filters, sorts et brouillon local, Brouillon local et restauration, Cas d'erreur, Chaîne complète, Colonnes, Construction de l'état frontend, Diagramme de séquence, Déclencheurs utilisateur (+10 more)

### Community 50 - "options"
Cohesion: 0.25
Nodes (11): options, assets, browser, inlineStyleLanguage, polyfills, styles, tsConfig, options (+3 more)

### Community 51 - "04 — Génération complète asynchrone"
Cohesion: 0.11
Nodes (18): 04 — Génération complète asynchrone, Cas d'erreur, Chaîne complète, Cleanup et expiration, Count, Création transactionnelle, Diagramme de séquence, Déclencheur utilisateur (+10 more)

### Community 52 - "05 — Export PDF/XLSX et téléchargement"
Cohesion: 0.11
Nodes (18): 05 — Export PDF/XLSX et téléchargement, Cas d'erreur, Chaîne complète, Création de l'export, Diagramme de séquence, Dispatch et sélection de l'interface, Déclencheurs utilisateur, En langage métier (+10 more)

### Community 53 - "Rapport d'avancement — Projet RHIS"
Cohesion: 0.11
Nodes (17): 1. Objectif actuel du projet, 2. Travaux réalisés, 3. Problèmes identifiés et corrigés, 4. Vérifications effectuées, 5. État actuel, 6. Prochaines étapes proposées, 7. Résumé, API REST et format de réponse (+9 more)

### Community 54 - "Rhis_report_gen"
Cohesion: 0.20
Nodes (9): newProjectRoot, projects, Rhis_report_gen, prefix, projectType, root, sourceRoot, $schema (+1 more)

### Community 55 - "mvnw"
Cohesion: 0.33
Nodes (6): mvnw script, clean(), die(), exec_maven(), set_java_home(), verbose()

### Community 56 - "01 — Sélection des datasets et chargement de la configuration"
Cohesion: 0.12
Nodes (17): 01 — Sélection des datasets et chargement de la configuration, 1. Chargement initial parallèle, 2. Lecture des datasets, 3. Découverte des relations, 4. Sélection UI et navigation, 5. Résolution de la route et chargement des fields, Cas d'erreur, Chaîne complète (+9 more)

### Community 57 - "build"
Cohesion: 0.25
Nodes (8): build, builder, configurations, defaultConfiguration, production, budgets, buildTarget, outputHashing

### Community 58 - "@schematics/angular:component"
Cohesion: 0.25
Nodes (8): schematics, skipTests, style, type, skipTests, type, @schematics/angular:component, @schematics/angular:service

### Community 59 - "package.json"
Cohesion: 0.25
Nodes (7): name, prettier, overrides, printWidth, singleQuote, private, version

### Community 60 - "ReportConfigurationLoader"
Cohesion: 0.46
Nodes (3): SelectedDataset, ReportConfigurationLoader, Injectable

### Community 61 - "06 — Authentification par cookies et refresh token"
Cohesion: 0.13
Nodes (15): 06 — Authentification par cookies et refresh token, Cas d'erreur, Diagramme de séquence — login, Diagramme de séquence — refresh, En langage métier, Flow login — déclencheur et chaîne, Flow refresh — backend uniquement, `/me` et logout (+7 more)

### Community 62 - "development"
Cohesion: 0.20
Nodes (10): serve, development, buildTarget, extractLicenses, fileReplacements, optimization, sourceMap, builder (+2 more)

### Community 63 - "scripts"
Cohesion: 0.33
Nodes (6): scripts, build, ng, start, test, watch

### Community 64 - "architect"
Cohesion: 0.40
Nodes (5): extract-i18n, test, builder, architect, builder

### Community 65 - "RhisApplication"
Cohesion: 0.60
Nodes (3): org.springframework.boot.autoconfigure.SpringBootApplication, org.springframework.scheduling.annotation.EnableScheduling, RhisApplication

### Community 66 - "ResolvedReportDefinition"
Cohesion: 0.40
Nodes (6): ResolvedFilter, ResolvedJoin, ResolvedJoinColumn, ResolvedReportDefinition, ResolvedSort, ReportSqlBuilderTest

### Community 72 - "flows/README.md"
Cohesion: 0.17
Nodes (6): Architecture transversale, Constats critiques confirmés, Flows fonctionnels et techniques RHIS, Frontière fonctionnelle observée, Vue d'ensemble, Vérification exécutée

### Community 73 - "03 — Preview synchrone du rapport"
Cohesion: 0.17
Nodes (12): 03 — Preview synchrone du rapport, Accès base et cardinalité, Cas d'erreur, Chaîne complète, Chemin retour et erreurs UI, Diagramme de séquence, Déclencheur utilisateur, En langage métier (+4 more)

### Community 74 - "Correction ciblée du layout de la page Export"
Cohesion: 0.18
Nodes (10): Cartes de format, Composition générale, Correction ciblée du layout de la page Export, Densité de l’état READY, Design validé — option A, Diagnostic, Objectif, Périmètre d’implémentation (+2 more)

### Community 76 - "Global Constraints"
Cohesion: 0.18
Nodes (10): Async Report Generation and Export Implementation Plan, Global Constraints, Task 1: Shared definition resolution and SQL variants, Task 2: Job persistence, public contracts, and owner security, Task 3: Bounded execution and streamed snapshot, Task 4: XLSX and PDF export workers, Task 5: Expiration, cancellation, abandoned jobs, and download, Task 6: Angular API, draft persistence, and generation submission (+2 more)

### Community 83 - "Report export vertical stepper design"
Cohesion: 0.20
Nodes (9): Accessibility, Error and edge states, Goal, Report export vertical stepper design, Responsive behavior, Technical scope, Validated format card — option B, Validated layout (+1 more)

### Community 84 - "File Map"
Cohesion: 0.22
Nodes (8): File Map, Global Constraints, Targeted Report Export Refactoring Implementation Plan, Task 1: Protect the duplicated polling behavior with characterization tests, Task 2: Apply the approved targeted domain naming, Task 3: Centralize the transient polling retry policy locally, Task 4: Simplify repeated template evaluation without extracting a component, Task 5: Run complete regression and production-build verification

### Community 85 - "Global Constraints"
Cohesion: 0.22
Nodes (8): Global Constraints, Report Export Front/Back KISS Refactoring Implementation Plan, Task 1: Corriger la reprise réseau du polling d’export, Task 2: Clarifier le naming HTTP et les dépendances Angular, Task 3: Restaurer la frontière d’authentification du workflow Report/Export, Task 4: Nommer explicitement l’enregistrement de progression backend, Task 5: Simplifier les détails internes backend sans nouvelle abstraction, Task 6: Validation end-to-end et contrôle de périmètre

### Community 86 - "Global Constraints"
Cohesion: 0.22
Nodes (8): Global Constraints, Report Builder Data Administration Figma Implementation Plan, Task 1: Create and inspect the target Figma file, Task 2: Establish visual foundations and the Components area, Task 3: Compose `01 — Dataset active`, Task 4: Compose inactive, search and unsaved states, Task 5: Compose save feedback variants, Task 6: Document responsive behavior and perform final QA

### Community 87 - "RhisReportGen"
Cohesion: 0.25
Nodes (7): Additional Resources, Building, Code scaffolding, Development server, RhisReportGen, Running end-to-end tests, Running unit tests

### Community 88 - "RHIS — documentation ciblée du flux de rapports"
Cohesion: 0.25
Nodes (7): Invariants à rendre explicites, Objectif, Périmètre backend, Périmètre frontend, RHIS — documentation ciblée du flux de rapports, Règles rédactionnelles, Validation

### Community 89 - "Étapes détaillées"
Cohesion: 0.29
Nodes (7): 1. Départ et état Angular, 2. Frontière HTTP et sécurité effective, 3. Controller et validation structurelle, 4. Résolution métier, 5. Construction SQL, 6. Exécution et mapping, Étapes détaillées

### Community 90 - "Global Constraints"
Cohesion: 0.29
Nodes (6): Global Constraints, Task 1: Reproduce legacy temporal values through the XLSX public seam, Task 2: Read canonical and legacy temporal representations, Task 3: Canonicalize all newly-created snapshots to ISO-8601, Task 4: Full verification, XLSX Temporal Snapshot Compatibility Implementation Plan

### Community 91 - "XLSX Temporal Snapshot Compatibility Design"
Cohesion: 0.29
Nodes (6): Context, Decision, Error handling, Scope, Verification, XLSX Temporal Snapshot Compatibility Design

### Community 92 - ".write"
Cohesion: 0.38
Nodes (3): FunctionalInterface, RowSink, RowsSource

### Community 93 - "Global Constraints"
Cohesion: 0.33
Nodes (5): Global Constraints, Report Export Vertical Stepper Implementation Plan, Task 1: Derived export workflow state, Task 2: Semantic wizard and progressive timeline, Task 3: Error states and regression verification

### Community 94 - "Global Constraints"
Cohesion: 0.33
Nodes (5): Global Constraints, Report Code Documentation Implementation Plan, Task 1: Document Angular report configuration responsibilities, Task 2: Document backend preview validation, SQL, and JDBC constraints, Task 3: Cross-project documentation-only verification

### Community 95 - "Global Constraints"
Cohesion: 0.33
Nodes (5): Global Constraints, RHIS End-to-End Flow Documentation Implementation Plan, Task 1: Map implemented flows, Task 2: Write flow documents, Task 3: Verify documentation

### Community 96 - "Global Constraints"
Cohesion: 0.40
Nodes (4): Global Constraints, Report Export Layout Correction Implementation Plan, Task 1: Alléger l’état READY et rendre les actions fluides, Task 2: Donner toute la largeur au workflow et contenir les cartes

### Community 97 - "Login détaillé"
Cohesion: 0.40
Nodes (5): 1. Validation frontend, 2. Authentification Spring Security, 3. Création des tokens, 4. Cookies et retour UI, Login détaillé

### Community 98 - "Independent report formats with PrimeNG implementation plan"
Cohesion: 0.50
Nodes (3): Implementation, Independent report formats with PrimeNG implementation plan, Verification

## Knowledge Gaps
- **488 isolated node(s):** `$schema`, `version`, `newProjectRoot`, `projectType`, `style` (+483 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **22 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `DataSetFieldType` connect `DataSetFieldType` to `UserEntity`, `org.springframework.data.jpa.repository.JpaRepository`, `DataSetEntity`, `ResolvedReportDefinition`, `XlsxReportExportWriter`, `org.junit.jupiter.api.Test`, `ReportJobProperties`, `DataSetInitializer`, `ReportSnapshotReader`, `DataSetField`, `ReportSnapshotMetadata`, `PdfReportExportWriter`, `ReportExportWriterTest`, `DataSetFieldResponse`?**
  _High betweenness centrality (0.018) - this node is a cross-community bridge._
- **Why does `DataSetEntity` connect `DataSetEntity` to `UserEntity`, `org.springframework.data.jpa.repository.JpaRepository`, `ResolvedReportDefinition`, `DataSetFieldType`, `org.junit.jupiter.api.Test`, `DataSetInitializer`, `DataSetField`, `ReportPreviewPostgresIntegrationTest.java`, `DataSetFieldResponse`?**
  _High betweenness centrality (0.016) - this node is a cross-community bridge._
- **Why does `UserEntity` connect `UserEntity` to `org.springframework.data.jpa.repository.JpaRepository`, `lombok.RequiredArgsConstructor`, `DataSetEntity`, `org.junit.jupiter.api.Test`, `UserPrincipal`, `DataSetInitializer`, `AuthServiceImpl.java`, `ReportGenerationEntity`, `UserService`, `ReportGenerationController`, `ReportGenerationService`, `ReportPreviewPostgresIntegrationTest.java`, `org.springframework.stereotype.Service`?**
  _High betweenness centrality (0.015) - this node is a cross-community bridge._
- **Are the 4 inferred relationships involving `ReportJobProperties` (e.g. with `.storage()` and `.keepsExportProgressMonotonicWhenWriterCallbacksDecreaseOrExceedTheMaximum()`) actually correct?**
  _`ReportJobProperties` has 4 INFERRED edges - model-reasoned connections that need verification._
- **What connects `$schema`, `version`, `newProjectRoot` to the rest of the system?**
  _488 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `org.springframework.data.jpa.repository.JpaRepository` be split into smaller, more focused modules?**
  _Cohesion score 0.06446886446886448 - nodes in this community are weakly interconnected._
- **Should `lombok.RequiredArgsConstructor` be split into smaller, more focused modules?**
  _Cohesion score 0.08599033816425121 - nodes in this community are weakly interconnected._