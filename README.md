# GFStudy

GameFramework Study

# *WSL* 终端下使用下面命令

`tree -I '*.meta'`
.
├── Base
│   ├── DataProvider
│   │   ├── DataProviderCreator.cs
│   │   ├── DataProvider.cs
│   │   ├── IDataProvider.cs
│   │   ├── IDataProviderHelper.cs
│   │   ├── ReadDataDependencyAssetEventArgs.cs
│   │   ├── ReadDataFailureEventArgs.cs
│   │   ├── ReadDataSuccessEventArgs.cs
│   │   └── ReadDataUpdateEventArgs.cs
│   ├── DataStruct
│   │   └── TypeNamePair.cs
│   ├── EventPool
│   │   ├── BaseEventArgs.cs
│   │   ├── EventPool.cs
│   │   ├── EventPool.Event.cs
│   │   └── EventPoolMode.cs
│   ├── GameFrameworkAction.cs
│   ├── GameFrameworkEntry.cs
│   ├── GameFrameworkEventArgs.cs
│   ├── GameFrameworkException.cs
│   ├── GameFrameworkFunc.cs
│   ├── GameFrameworkLinkedList.cs
│   ├── GameFrameworkLinkedListRange.cs
│   ├── GameFrameworkModule.cs
│   ├── GameFrameworkMultiDictionary.cs
│   ├── GameFrameworkSerializer.cs
│   ├── Log
│   │   ├── GameFrameworkLog.cs
│   │   ├── GameFrameworkLog.ILogHelper.cs
│   │   └── GameFrameworkLogLevel.cs
│   ├── ReferencePool
│   │   ├── IReference.cs
│   │   ├── ReferencePool.cs
│   │   ├── ReferencePoolInfo.cs
│   │   └── ReferencePool.ReferenceCollection.cs
│   ├── TaskPool
│   │   ├── ITaskAgent.cs
│   │   ├── StartTaskStatus.cs
│   │   ├── TaskBase.cs
│   │   ├── TaskInfo.cs
│   │   ├── TaskPool.cs
│   │   └── TaskStatus.cs
│   ├── Variable
│   │   ├── GenericVariable.cs
│   │   └── Variable.cs
│   └── Version
│       ├── Version.cs
│       └── Version.IVersionHelper.cs
├── Config
│   ├── ConfigManager.ConfigData.cs
│   ├── ConfigManager.cs
│   ├── IConfigHelper.cs
│   └── IConfigManager.cs
├── DataNode
│   ├── DataNodeManager.cs
│   ├── DataNodeManager.DataNode.cs
│   ├── IDataNode.cs
│   └── IDataNodeManager.cs
├── DataTable
│   ├── DataTableBase.cs
│   ├── DataTableManager.cs
│   ├── DataTableManager.DataTable.cs
│   ├── IDataRow.cs
│   ├── IDataTable.cs
│   ├── IDataTableHelper.cs
│   └── IDataTableManager.cs
├── Debugger
│   ├── DebuggerManager.cs
│   ├── DebuggerManager.DebuggerWindowGroup.cs
│   ├── IDebuggerManager.cs
│   ├── IDebuggerWindow.cs
│   └── IDebuggerWindowGroup.cs
├── Download
│   ├── Constant.cs
│   ├── DownloadAgentHelperCompleteEventArgs.cs
│   ├── DownloadAgentHelperErrorEventArgs.cs
│   ├── DownloadAgentHelperUpdateBytesEventArgs.cs
│   ├── DownloadAgentHelperUpdateLengthEventArgs.cs
│   ├── DownloadFailureEventArgs.cs
│   ├── DownloadManager.cs
│   ├── DownloadManager.DownloadAgent.cs
│   ├── DownloadManager.DownloadCounter.cs
│   ├── DownloadManager.DownloadCounter.DownloadCounterNode.cs
│   ├── DownloadManager.DownloadTask.cs
│   ├── DownloadManager.DownloadTaskStatus.cs
│   ├── DownloadStartEventArgs.cs
│   ├── DownloadSuccessEventArgs.cs
│   ├── DownloadUpdateEventArgs.cs
│   ├── IDownloadAgentHelper.cs
│   └── IDownloadManager.cs
├── Entity
│   ├── EntityManager.cs
│   ├── EntityManager.EntityGroup.cs
│   ├── EntityManager.EntityInfo.cs
│   ├── EntityManager.EntityInstanceObject.cs
│   ├── EntityManager.EntityStatus.cs
│   ├── EntityManager.ShowEntityInfo.cs
│   ├── HideEntityCompleteEventArgs.cs
│   ├── IEntity.cs
│   ├── IEntityGroup.cs
│   ├── IEntityGroupHelper.cs
│   ├── IEntityHelper.cs
│   ├── IEntityManager.cs
│   ├── ShowEntityDependencyAssetEventArgs.cs
│   ├── ShowEntityFailureEventArgs.cs
│   ├── ShowEntitySuccessEventArgs.cs
│   └── ShowEntityUpdateEventArgs.cs
├── Event
│   ├── EventManager.cs
│   ├── GameEventArgs.cs
│   └── IEventManager.cs
├── FileSystem
│   ├── CommonFileSystemStream.cs
│   ├── FileInfo.cs
│   ├── FileSystemAccess.cs
│   ├── FileSystem.BlockData.cs
│   ├── FileSystem.cs
│   ├── FileSystem.HeaderData.cs
│   ├── FileSystemManager.cs
│   ├── FileSystemStream.cs
│   ├── FileSystem.StringData.cs
│   ├── IFileSystem.cs
│   ├── IFileSystemHelper.cs
│   └── IFileSystemManager.cs
├── Fsm
│   ├── FsmBase.cs
│   ├── Fsm.cs
│   ├── FsmManager.cs
│   ├── FsmState.cs
│   ├── IFsm.cs
│   └── IFsmManager.cs
├── Localization
│   ├── ILocalizationHelper.cs
│   ├── ILocalizationManager.cs
│   ├── Language.cs
│   └── LocalizationManager.cs
├── Network
│   ├── AddressFamily.cs
│   ├── INetworkChannel.cs
│   ├── INetworkChannelHelper.cs
│   ├── INetworkManager.cs
│   ├── IPacketHandler.cs
│   ├── IPacketHeader.cs
│   ├── NetworkClosedEventArgs.cs
│   ├── NetworkConnectedEventArgs.cs
│   ├── NetworkCustomErrorEventArgs.cs
│   ├── NetworkErrorCode.cs
│   ├── NetworkErrorEventArgs.cs
│   ├── NetworkManager.ConnectState.cs
│   ├── NetworkManager.cs
│   ├── NetworkManager.HeartBeatState.cs
│   ├── NetworkManager.NetworkChannelBase.cs
│   ├── NetworkManager.ReceiveState.cs
│   ├── NetworkManager.SendState.cs
│   ├── NetworkManager.TcpNetworkChannel.cs
│   ├── NetworkManager.TcpWithSyncReceiveNetworkChannel.cs
│   ├── NetworkMissHeartBeatEventArgs.cs
│   ├── Packet.cs
│   └── ServiceType.cs
├── ObjectPool
│   ├── IObjectPool.cs
│   ├── IObjectPoolManager.cs
│   ├── ObjectBase.cs
│   ├── ObjectInfo.cs
│   ├── ObjectPoolBase.cs
│   ├── ObjectPoolManager.cs
│   ├── ObjectPoolManager.Object.cs
│   ├── ObjectPoolManager.ObjectPool.cs
│   └── ReleaseObjectFilterCallback.cs
├── Procedure
│   ├── IProcedureManager.cs
│   ├── ProcedureBase.cs
│   └── ProcedureManager.cs
├── Properties
│   └── AssemblyInfo.cs
├── Resource
│   ├── ApplyResourcesCompleteCallback.cs
│   ├── CheckResourcesCompleteCallback.cs
│   ├── CheckVersionListResult.cs
│   ├── Constant.cs
│   ├── DecryptResourceCallback.cs
│   ├── HasAssetResult.cs
│   ├── ILoadResourceAgentHelper.cs
│   ├── InitResourcesCompleteCallback.cs
│   ├── IResourceGroupCollection.cs
│   ├── IResourceGroup.cs
│   ├── IResourceHelper.cs
│   ├── IResourceManager.cs
│   ├── LoadAssetCallbacks.cs
│   ├── LoadAssetDependencyAssetCallback.cs
│   ├── LoadAssetFailureCallback.cs
│   ├── LoadAssetSuccessCallback.cs
│   ├── LoadAssetUpdateCallback.cs
│   ├── LoadBinaryCallbacks.cs
│   ├── LoadBinaryFailureCallback.cs
│   ├── LoadBinarySuccessCallback.cs
│   ├── LoadBytesCallbacks.cs
│   ├── LoadBytesFailureCallback.cs
│   ├── LoadBytesSuccessCallback.cs
│   ├── LoadResourceAgentHelperErrorEventArgs.cs
│   ├── LoadResourceAgentHelperLoadCompleteEventArgs.cs
│   ├── LoadResourceAgentHelperParseBytesCompleteEventArgs.cs
│   ├── LoadResourceAgentHelperReadBytesCompleteEventArgs.cs
│   ├── LoadResourceAgentHelperReadFileCompleteEventArgs.cs
│   ├── LoadResourceAgentHelperUpdateEventArgs.cs
│   ├── LoadResourceProgress.cs
│   ├── LoadResourceStatus.cs
│   ├── LoadSceneCallbacks.cs
│   ├── LoadSceneDependencyAssetCallback.cs
│   ├── LoadSceneFailureCallback.cs
│   ├── LoadSceneSuccessCallback.cs
│   ├── LoadSceneUpdateCallback.cs
│   ├── LocalVersionList.cs
│   ├── LocalVersionList.FileSystem.cs
│   ├── LocalVersionList.Resource.cs
│   ├── PackageVersionList.Asset.cs
│   ├── PackageVersionList.cs
│   ├── PackageVersionList.FileSystem.cs
│   ├── PackageVersionList.Resource.cs
│   ├── PackageVersionList.ResourceGroup.cs
│   ├── PackageVersionListSerializer.cs
│   ├── ReadOnlyVersionListSerializer.cs
│   ├── ReadWriteVersionListSerializer.cs
│   ├── ResourceApplyFailureEventArgs.cs
│   ├── ResourceApplyStartEventArgs.cs
│   ├── ResourceApplySuccessEventArgs.cs
│   ├── ResourceManager.AssetInfo.cs
│   ├── ResourceManager.cs
│   ├── ResourceManager.LoadType.cs
│   ├── ResourceManager.ReadWriteResourceInfo.cs
│   ├── ResourceManager.ResourceChecker.CheckInfo.CheckStatus.cs
│   ├── ResourceManager.ResourceChecker.CheckInfo.cs
│   ├── ResourceManager.ResourceChecker.CheckInfo.LocalVersionInfo.cs
│   ├── ResourceManager.ResourceChecker.CheckInfo.RemoteVersionInfo.cs
│   ├── ResourceManager.ResourceChecker.cs
│   ├── ResourceManager.ResourceGroupCollection.cs
│   ├── ResourceManager.ResourceGroup.cs
│   ├── ResourceManager.ResourceInfo.cs
│   ├── ResourceManager.ResourceIniter.cs
│   ├── ResourceManager.ResourceLoader.AssetObject.cs
│   ├── ResourceManager.ResourceLoader.cs
│   ├── ResourceManager.ResourceLoader.LoadAssetTask.cs
│   ├── ResourceManager.ResourceLoader.LoadBinaryInfo.cs
│   ├── ResourceManager.ResourceLoader.LoadDependencyAssetTask.cs
│   ├── ResourceManager.ResourceLoader.LoadResourceAgent.cs
│   ├── ResourceManager.ResourceLoader.LoadResourceTaskBase.cs
│   ├── ResourceManager.ResourceLoader.LoadSceneTask.cs
│   ├── ResourceManager.ResourceLoader.ResourceObject.cs
│   ├── ResourceManager.ResourceNameComparer.cs
│   ├── ResourceManager.ResourceName.cs
│   ├── ResourceManager.ResourceUpdater.ApplyInfo.cs
│   ├── ResourceManager.ResourceUpdater.cs
│   ├── ResourceManager.ResourceUpdater.UpdateInfo.cs
│   ├── ResourceManager.ResourceVerifier.cs
│   ├── ResourceManager.ResourceVerifier.VerifyInfo.cs
│   ├── ResourceManager.VersionListProcessor.cs
│   ├── ResourceMode.cs
│   ├── ResourcePackVersionList.cs
│   ├── ResourcePackVersionList.Resource.cs
│   ├── ResourcePackVersionListSerializer.cs
│   ├── ResourceUpdateAllCompleteEventArgs.cs
│   ├── ResourceUpdateChangedEventArgs.cs
│   ├── ResourceUpdateFailureEventArgs.cs
│   ├── ResourceUpdateStartEventArgs.cs
│   ├── ResourceUpdateSuccessEventArgs.cs
│   ├── ResourceVerifyFailureEventArgs.cs
│   ├── ResourceVerifyStartEventArgs.cs
│   ├── ResourceVerifySuccessEventArgs.cs
│   ├── UnloadSceneCallbacks.cs
│   ├── UnloadSceneFailureCallback.cs
│   ├── UnloadSceneSuccessCallback.cs
│   ├── UpdatableVersionList.Asset.cs
│   ├── UpdatableVersionList.cs
│   ├── UpdatableVersionList.FileSystem.cs
│   ├── UpdatableVersionList.Resource.cs
│   ├── UpdatableVersionList.ResourceGroup.cs
│   ├── UpdatableVersionListSerializer.cs
│   ├── UpdateResourcesCompleteCallback.cs
│   ├── UpdateVersionListCallbacks.cs
│   ├── UpdateVersionListFailureCallback.cs
│   ├── UpdateVersionListSuccessCallback.cs
│   └── VerifyResourcesCompleteCallback.cs
├── Scene
│   ├── ISceneManager.cs
│   ├── LoadSceneDependencyAssetEventArgs.cs
│   ├── LoadSceneFailureEventArgs.cs
│   ├── LoadSceneSuccessEventArgs.cs
│   ├── LoadSceneUpdateEventArgs.cs
│   ├── SceneManager.cs
│   ├── UnloadSceneFailureEventArgs.cs
│   └── UnloadSceneSuccessEventArgs.cs
├── Setting
│   ├── ISettingHelper.cs
│   ├── ISettingManager.cs
│   └── SettingManager.cs
├── Sound
│   ├── Constant.cs
│   ├── ISoundAgent.cs
│   ├── ISoundAgentHelper.cs
│   ├── ISoundGroup.cs
│   ├── ISoundGroupHelper.cs
│   ├── ISoundHelper.cs
│   ├── ISoundManager.cs
│   ├── PlaySoundDependencyAssetEventArgs.cs
│   ├── PlaySoundErrorCode.cs
│   ├── PlaySoundFailureEventArgs.cs
│   ├── PlaySoundParams.cs
│   ├── PlaySoundSuccessEventArgs.cs
│   ├── PlaySoundUpdateEventArgs.cs
│   ├── ResetSoundAgentEventArgs.cs
│   ├── SoundManager.cs
│   ├── SoundManager.PlaySoundInfo.cs
│   ├── SoundManager.SoundAgent.cs
│   └── SoundManager.SoundGroup.cs
├── UI
│   ├── CloseUIFormCompleteEventArgs.cs
│   ├── IUIForm.cs
│   ├── IUIFormHelper.cs
│   ├── IUIGroup.cs
│   ├── IUIGroupHelper.cs
│   ├── IUIManager.cs
│   ├── OpenUIFormDependencyAssetEventArgs.cs
│   ├── OpenUIFormFailureEventArgs.cs
│   ├── OpenUIFormSuccessEventArgs.cs
│   ├── OpenUIFormUpdateEventArgs.cs
│   ├── UIManager.cs
│   ├── UIManager.OpenUIFormInfo.cs
│   ├── UIManager.UIFormInstanceObject.cs
│   ├── UIManager.UIGroup.cs
│   └── UIManager.UIGroup.UIFormInfo.cs
├── Utility
│   ├── Utility.Assembly.cs
│   ├── Utility.Compression.cs
│   ├── Utility.Compression.ICompressionHelper.cs
│   ├── Utility.Converter.cs
│   ├── Utility.cs
│   ├── Utility.Encryption.cs
│   ├── Utility.Json.cs
│   ├── Utility.Json.IJsonHelper.cs
│   ├── Utility.Marshal.cs
│   ├── Utility.Path.cs
│   ├── Utility.Random.cs
│   ├── Utility.Text.cs
│   ├── Utility.Text.ITextHelper.cs
│   ├── Utility.Verifier.Crc32.cs
│   └── Utility.Verifier.cs
└── WebRequest
├── Constant.cs
├── IWebRequestAgentHelper.cs
├── IWebRequestManager.cs
├── WebRequestAgentHelperCompleteEventArgs.cs
├── WebRequestAgentHelperErrorEventArgs.cs
├── WebRequestFailureEventArgs.cs
├── WebRequestManager.cs
├── WebRequestManager.WebRequestAgent.cs
├── WebRequestManager.WebRequestTask.cs
├── WebRequestManager.WebRequestTaskStatus.cs
├── WebRequestStartEventArgs.cs
└── WebRequestSuccessEventArgs.cs
