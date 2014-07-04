
EXTRA_DIST =  

# Warning: This is an automatically generated file, do not edit!

if ENABLE_DEBUG
ASSEMBLY_COMPILER_COMMAND = dmcs
ASSEMBLY_COMPILER_FLAGS =  -noconfig -codepage:utf8 -warn:4 -optimize- "-nowarn:108;628;162;219;414;618;168;169;612;114" -debug "-define:$(DefineConstants);DEBUG;TRACE"
ASSEMBLY = bin/\$\(TargetFrameworkVersion\)/Debug/MySql.Data.dll
ASSEMBLY_MDB = $(ASSEMBLY).mdb
COMPILE_TARGET = library
PROJECT_REFERENCES = 
BUILD_DIR = bin/$(TargetFrameworkVersion)/Debug/

MYSQL_DATA_DLL_MDB_SOURCE=bin/$(TargetFrameworkVersion)/Debug/MySql.Data.dll.mdb
MYSQL_DATA_DLL_MDB=$(BUILD_DIR)/MySql.Data.dll.mdb

endif

if ENABLE_RELEASE
ASSEMBLY_COMPILER_COMMAND = dmcs
ASSEMBLY_COMPILER_FLAGS =  -noconfig -codepage:utf8 -warn:4 -optimize+ "-nowarn:108;628;162;219;414;618;168;169;612;114" "-define:$(DefineConstants);TRACE"
ASSEMBLY = bin/\$\(TargetFrameworkVersion\)/Release/MySql.Data.dll
ASSEMBLY_MDB = 
COMPILE_TARGET = library
PROJECT_REFERENCES = 
BUILD_DIR = bin/$(TargetFrameworkVersion)/Release/

MYSQL_DATA_DLL_MDB=

endif

AL=al
SATELLITE_ASSEMBLY_NAME=$(notdir $(basename $(ASSEMBLY))).resources.dll

PROGRAMFILES = \
	$(MYSQL_DATA_DLL_MDB)  

LINUX_PKGCONFIG = \
	$(MYSQL_DATA_SCHUMIX_PC)  


RESGEN=resgen2
	
all: $(ASSEMBLY) $(PROGRAMFILES) $(LINUX_PKGCONFIG) 

FILES = \
	Authentication/AuthenticationManager.cs \
	Authentication/MySQLAuthenticationPlugin.cs \
	Authentication/NativePasswordPlugins.cs \
	Authentication/Sha256AuthenticationPlugin.cs \
	Authentication/WindowsAuthenticationPlugin.cs \
	BulkLoader.cs \
	CharSetMap.cs \
	command.cs \
	CommandBuilder.cs \
	common/Cache.cs \
	common/ContextString.cs \
	common/LowResolutionStopwatch.cs \
	common/MyNetworkStream.cs \
	common/MySqlTokenizer.cs \
	common/NamedPipeStream.cs \
	common/NativeMethods.cs \
	common/Platform.cs \
	common/QueryNormalizer.cs \
	common/SharedMemoryStream.cs \
	common/StreamCreator.cs \
	common/StringUtility.cs \
	common/Version.cs \
	CompressedStream.cs \
	Connection.cs \
	Crypt.cs \
	dataadapter.cs \
	datareader.cs \
	Driver.cs \
	Exception.cs \
	extensions/NonRT/MySqlCommand.cs \
	extensions/NonRT/MySqlConnection.cs \
	extensions/NonRT/MySqlConnectionStringBuilder.cs \
	extensions/NonRT/MySqlDataReader.cs \
	extensions/NonRT/MySqlDateTime.cs \
	extensions/NonRT/MySqlParameter.cs \
	extensions/NonRT/MySqlParameterCollection.cs \
	extensions/NonRT/MySqlTrace.cs \
	extensions/NonRT/MySqlTransaction.cs \
	Field.cs \
	Installer.cs \
	Interceptors/CommandInterceptor.cs \
	Interceptors/Interceptor.cs \
	Interceptors/ExceptionInterceptor.cs \
	ISSchemaProvider.cs \
	Memcached/BinaryClient.cs \
	Memcached/MemcachedException.cs \
	Memcached/TextClient.cs \
	Memcached/Client.cs \
	MySqlClientFactory.cs \
	MySqlClientPermission.cs \
	MySqlConfiguration.cs \
	MySqlConnectionStringBuilder.cs \
	MysqlDefs.cs \
	MySqlError.cs \
	MySqlHelper.cs \
	MySqlPacket.cs \
	MySqlClientPermissionAttribute.cs \
	MySqlPool.cs \
	MySqlPoolManager.cs \
	MySqlPromotableTransaction.cs \
	MySqlScript.cs \
	MySqlSecurityPermission.cs \
	MySqlStream.cs \
	NativeDriver.cs \
	parameter.cs \
	parameter_collection.cs \
	PerformanceMonitor.cs \
	PreparableStatement.cs \
	ProcedureCache.cs \
	Properties/AssemblyInfo.cs \
	Properties/VersionInfo.cs \
	Replication/ReplicationConfiguration.cs \
	Replication/ReplicationManager.cs \
	Replication/ReplicationRoundRobinServerGroup.cs \
	Replication/ReplicationServer.cs \
	Replication/ReplicationServerGroup.cs \
	ResultSet.cs \
	Schema.cs \
	SchemaProvider.cs \
	Statement.cs \
	StoredProcedure.cs \
	SystemPerformanceMonitor.cs \
	TableCache.cs \
	TimedStream.cs \
	TracingDriver.cs \
	transaction.cs \
	Types/MetaData.cs \
	Types/MySqlBinary.cs \
	Types/MySqlBit.cs \
	Types/MySqlByte.cs \
	Types/MySqlConversionException.cs \
	Types/MySqlDateTime.cs \
	Types/MySqlDecimal.cs \
	Types/MySqlDouble.cs \
	Types/MySqlGeometry.cs \
	Types/MySqlGuid.cs \
	Types/MySqlInt16.cs \
	Types/MySqlInt32.cs \
	Types/MySqlInt64.cs \
	Types/MySqlSingle.cs \
	Types/MySqlString.cs \
	Types/MySqlTime.cs \
	Types/MySqlUByte.cs \
	Types/MySqlUInt16.cs \
	Types/MySqlUInt32.cs \
	Types/MySqlUInt64.cs \
	Types/MySqlValue.cs \
	zlib/Adler32.cs \
	zlib/Deflate.cs \
	zlib/InfBlocks.cs \
	zlib/InfCodes.cs \
	zlib/Inflate.cs \
	zlib/InfTree.cs \
	zlib/StaticTree.cs \
	zlib/SupportClass.cs \
	zlib/Tree.cs \
	zlib/ZInputStream.cs \
	zlib/Zlib.cs \
	zlib/ZOutputStream.cs \
	zlib/ZStream.cs \
	zlib/ZStreamException.cs \
	Properties/Resources.Designer.cs 

DATA_FILES = 

RESOURCES = \
	Properties/ReservedWords.txt,MySql.Data.MySqlClient.Properties.ReservedWords.txt \
	Properties/Resources.resx,MySql.Data.MySqlClient.Properties.Resources.resources 

EXTRAS = \
	Properties/keywords.txt \
	../../CHANGES \
	docs/MySqlCommand.xml \
	docs/MySqlCommandBuilder.xml \
	docs/MySqlConnection.xml \
	docs/MySqlConnectionStringBuilder.xml \
	docs/MySqlDataAdapter.xml \
	docs/MySqlDataReader.xml \
	docs/MySqlException.xml \
	docs/MySqlHelper.xml \
	docs/MySqlParameter.xml \
	docs/MySqlParameterCollection.xml \
	docs/MySqlTransaction.xml \
	mysql.data.schumix.pc.in 

REFERENCES =  \
	System \
	System.Configuration \
	System.Configuration.Install \
	System.Data \
	System.Design \
	System.Drawing \
	System.Management \
	System.Security \
	System.Transactions \
	System.Xml

DLL_REFERENCES = 

CLEANFILES = $(PROGRAMFILES) $(LINUX_PKGCONFIG) 

include $(top_srcdir)/Makefile.include

MYSQL_DATA_SCHUMIX_PC = $(BUILD_DIR)/mysql.data.schumix.pc

$(eval $(call emit-deploy-wrapper,MYSQL_DATA_SCHUMIX_PC,mysql.data.schumix.pc))


$(eval $(call emit_resgen_targets))
$(build_xamlg_list): %.xaml.g.cs: %.xaml
	xamlg '$<'

$(ASSEMBLY_MDB): $(ASSEMBLY)

$(ASSEMBLY): $(build_sources) $(build_resources) $(build_datafiles) $(DLL_REFERENCES) $(PROJECT_REFERENCES) $(build_xamlg_list) $(build_satellite_assembly_list)
	mkdir -p $(shell dirname $(ASSEMBLY))
	$(ASSEMBLY_COMPILER_COMMAND) $(ASSEMBLY_COMPILER_FLAGS) -out:$(ASSEMBLY) -target:$(COMPILE_TARGET) $(build_sources_embed) $(build_resources_embed) $(build_references_ref)
