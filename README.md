     Build a complete Android Marketplace app from scratch using Kotlin and Jetpack Compose.                
  Package name: com.example.marketplace                     
  App name: MarketPlace

  Use EXACTLY these library versions (gradle/libs.versions.toml):

  [versions]
  agp = "8.8.1"
  kotlin = "2.0.0"
  ksp = "2.0.0-1.0.21"
  coreKtx = "1.16.0"                                                                                     
  junit = "4.13.2"
  junitVersion = "1.3.0"                                                                                 
  espressoCore = "3.7.0"                                                                                 
  lifecycleRuntimeKtx = "2.8.7"
  activityCompose = "1.9.3"                                                                              
  composeBom = "2024.09.00"                                                                              
  hilt = "2.51.1"
  hiltExt = "1.2.0"                                                                                      
  room = "2.6.1"                                            
  workManager = "2.9.1"                                                                                  
  coil = "2.7.0"                                                                                         
  navigation = "2.8.3"
  coroutines = "1.9.0"                                                                                   
  gson = "2.11.0"                                           
  securityCrypto = "1.1.0-alpha06"                                                                       
  mockitoCore = "5.12.0"
  mockitoKotlin = "5.4.0"                                                                                
  coroutinesTest = "1.9.0"                                  
  archCoreTesting = "2.2.0"                                                                              
  turbine = "1.1.0"                                         
                                                                                                         
  [libraries]                                               
  androidx-core-ktx = { group = "androidx.core", name = "core-ktx", version.ref = "coreKtx" }            
  junit = { group = "junit", name = "junit", version.ref = "junit" }
  androidx-junit = { group = "androidx.test.ext", name = "junit", version.ref = "junitVersion" }         
  androidx-espresso-core = { group = "androidx.test.espresso", name = "espresso-core", version.ref =
  "espressoCore" }                                                                                       
  androidx-lifecycle-runtime-ktx = { group = "androidx.lifecycle", name = "lifecycle-runtime-ktx",
  version.ref = "lifecycleRuntimeKtx" }                                                                  
  androidx-lifecycle-viewmodel-compose = { group = "androidx.lifecycle", name =
  "lifecycle-viewmodel-compose", version.ref = "lifecycleRuntimeKtx" }                                   
  androidx-lifecycle-runtime-compose = { group = "androidx.lifecycle", name =
  "lifecycle-runtime-compose", version.ref = "lifecycleRuntimeKtx" }                                     
  androidx-activity-compose = { group = "androidx.activity", name = "activity-compose", version.ref =
  "activityCompose" }                                                                                    
  androidx-compose-bom = { group = "androidx.compose", name = "compose-bom", version.ref = "composeBom" }
  androidx-ui = { group = "androidx.compose.ui", name = "ui" }                                           
  androidx-ui-graphics = { group = "androidx.compose.ui", name = "ui-graphics" }
  androidx-ui-tooling = { group = "androidx.compose.ui", name = "ui-tooling" }                           
  androidx-ui-tooling-preview = { group = "androidx.compose.ui", name = "ui-tooling-preview" }
  androidx-ui-test-manifest = { group = "androidx.compose.ui", name = "ui-test-manifest" }               
                                                            
─────────────────────────────────────────────────────────────────────────────────────────────────────────
❯                                                           
─────────────────────────────────────────────────────────────────────────────────────────────────────────
  ⏵⏵ accept edits on (shift+tab to cycle) · esc to interrupt
  mockitoKotlin = "5.4.0"
  coroutinesTest = "1.9.0"
  archCoreTesting = "2.2.0"
  turbine = "1.1.0"

  [libraries]
  androidx-core-ktx = { group = "androidx.core", name = "core-ktx", version.ref = "coreKtx" }
  junit = { group = "junit", name = "junit", version.ref = "junit" }
  androidx-junit = { group = "androidx.test.ext", name = "junit", version.ref = "junitVersion" }
  androidx-espresso-core = { group = "androidx.test.espresso", name = "espresso-core", version.ref =
  "espressoCore" }
  androidx-lifecycle-runtime-ktx = { group = "androidx.lifecycle", name = "lifecycle-runtime-ktx",
  version.ref = "lifecycleRuntimeKtx" }
  androidx-lifecycle-viewmodel-compose = { group = "androidx.lifecycle", name =
  "lifecycle-viewmodel-compose", version.ref = "lifecycleRuntimeKtx" }
  androidx-lifecycle-runtime-compose = { group = "androidx.lifecycle", name =
  "lifecycle-runtime-compose", version.ref = "lifecycleRuntimeKtx" }
  androidx-activity-compose = { group = "androidx.activity", name = "activity-compose", version.ref =
  "activityCompose" }
  androidx-compose-bom = { group = "androidx.compose", name = "compose-bom", version.ref = "composeBom" }
  androidx-ui = { group = "androidx.compose.ui", name = "ui" }
  androidx-ui-graphics = { group = "androidx.compose.ui", name = "ui-graphics" }
  androidx-ui-tooling = { group = "androidx.compose.ui", name = "ui-tooling" }
  androidx-ui-tooling-preview = { group = "androidx.compose.ui", name = "ui-tooling-preview" }
  androidx-ui-test-manifest = { group = "androidx.compose.ui", name = "ui-test-manifest" }
  androidx-ui-test-junit4 = { group = "androidx.compose.ui", name = "ui-test-junit4" }
  androidx-material3 = { group = "androidx.compose.material3", name = "material3" }                      
   
─────────────────────────────────────────────────────────────────────────────────────────────────────────
❯                                                           
─────────────────────────────────────────────────────────────────────────────────────────────────────────
  ⏵⏵ accept edits on (shift+tab to cycle) · esc to interrupt
  mockitoKotlin = "5.4.0"
  coroutinesTest = "1.9.0"
  archCoreTesting = "2.2.0"
  turbine = "1.1.0"

  [libraries]
  androidx-core-ktx = { group = "androidx.core", name = "core-ktx", version.ref = "coreKtx" }
  junit = { group = "junit", name = "junit", version.ref = "junit" }
  androidx-junit = { group = "androidx.test.ext", name = "junit", version.ref = "junitVersion" }
  androidx-espresso-core = { group = "androidx.test.espresso", name = "espresso-core", version.ref =
  "espressoCore" }
  androidx-lifecycle-runtime-ktx = { group = "androidx.lifecycle", name = "lifecycle-runtime-ktx",
  version.ref = "lifecycleRuntimeKtx" }
  androidx-lifecycle-viewmodel-compose = { group = "androidx.lifecycle", name =
  "lifecycle-viewmodel-compose", version.ref = "lifecycleRuntimeKtx" }
  androidx-lifecycle-runtime-compose = { group = "androidx.lifecycle", name =
  "lifecycle-runtime-compose", version.ref = "lifecycleRuntimeKtx" }
  androidx-activity-compose = { group = "androidx.activity", name = "activity-compose", version.ref =
  "activityCompose" }
  androidx-compose-bom = { group = "androidx.compose", name = "compose-bom", version.ref = "composeBom" }
  androidx-ui = { group = "androidx.compose.ui", name = "ui" }
  androidx-ui-graphics = { group = "androidx.compose.ui", name = "ui-graphics" }
  androidx-ui-tooling = { group = "androidx.compose.ui", name = "ui-tooling" }
  androidx-ui-tooling-preview = { group = "androidx.compose.ui", name = "ui-tooling-preview" }
  androidx-ui-test-manifest = { group = "androidx.compose.ui", name = "ui-test-manifest" }
  androidx-ui-test-junit4 = { group = "androidx.compose.ui", name = "ui-test-junit4" }
  androidx-material3 = { group = "androidx.compose.material3", name = "material3" }
  androidx-material-icons = { group = "androidx.compose.material", name = "material-icons-extended" }
  hilt-android = { group = "com.google.dagger", name = "hilt-android", version.ref = "hilt" }            
  hilt-android-compiler = { group = "com.google.dagger", name = "hilt-android-compiler", version.ref =
  "hilt" }                                                                                               
  hilt-navigation-compose = { group = "androidx.hilt", name = "hilt-navigation-compose", version.ref =
  "hiltExt" }                                                                                            
  hilt-work = { group = "androidx.hilt", name = "hilt-work", version.ref = "hiltExt" }
  hilt-compiler = { group = "androidx.hilt", name = "hilt-compiler", version.ref = "hiltExt" }           
  room-runtime = { group = "androidx.room", name = "room-runtime", version.ref = "room" }                
  room-compiler = { group = "androidx.room", name = "room-compiler", version.ref = "room" }              
  room-ktx = { group = "androidx.room", name = "room-ktx", version.ref = "room" }                        
  work-runtime-ktx = { group = "androidx.work", name = "work-runtime-ktx", version.ref = "workManager" }
  coil-compose = { group = "io.coil-kt", name = "coil-compose", version.ref = "coil" }                   
  navigation-compose = { group = "androidx.navigation", name = "navigation-compose", version.ref =
  "navigation" }                                                                                         
  kotlinx-coroutines-android = { group = "org.jetbrains.kotlinx", name = "kotlinx-coroutines-android",
  version.ref = "coroutines" }                                                                           
  gson = { group = "com.google.code.gson", name = "gson", version.ref = "gson" }
  security-crypto = { group = "androidx.security", name = "security-crypto", version.ref =               
  "securityCrypto" }                                                                                     
  mockito-core = { group = "org.mockito", name = "mockito-core", version.ref = "mockitoCore" }
  mockito-kotlin = { group = "org.mockito.kotlin", name = "mockito-kotlin", version.ref = "mockitoKotlin"
   }                                                                                                     
  kotlinx-coroutines-test = { group = "org.jetbrains.kotlinx", name = "kotlinx-coroutines-test",         
  version.ref = "coroutinesTest" }                                                                       
  arch-core-testing = { group = "androidx.arch.core", name = "core-testing", version.ref =
  "archCoreTesting" }                                                                                    
  turbine = { group = "app.cash.turbine", name = "turbine", version.ref = "turbine" }
                                                                                                         
  [plugins]
  android-application = { id = "com.android.application", version.ref = "agp" }                          
  kotlin-android = { id = "org.jetbrains.kotlin.android", version.ref = "kotlin" }
  kotlin-compose = { id = "org.jetbrains.kotlin.plugin.compose", version.ref = "kotlin" }                
  hilt = { id = "com.google.dagger.hilt.android", version.ref = "hilt" }
  ksp = { id = "com.google.devtools.ksp", version.ref = "ksp" }                                          
                                                            
  ---                                                                                                    
                                                            
  Root build.gradle.kts:                                                                                 
  plugins {                                                 
      alias(libs.plugins.android.application) apply false
      alias(libs.plugins.kotlin.android) apply false
      alias(libs.plugins.kotlin.compose) apply false                                                     
      alias(libs.plugins.hilt) apply false
      alias(libs.plugins.ksp) apply false                                                                
  }                                                         

  ---

  app/build.gradle.kts:                                                                                  
  plugins {
      alias(libs.plugins.android.application)                                                            
      alias(libs.plugins.kotlin.android)                    
      alias(libs.plugins.kotlin.compose)
      alias(libs.plugins.hilt)
      alias(libs.plugins.ksp)
  }                                                                                                      
   
  android {                                                                                              
      namespace = "com.example.marketplace"                 
      compileSdk = 35
      defaultConfig {
          applicationId = "com.example.marketplace"
          minSdk = 24                                                                                    
          targetSdk = 35
          versionCode = 1                                                                                
          versionName = "1.0"                               
          testInstrumentationRunner = "androidx.test.runner.AndroidJUnitRunner"
      }                                                                                                  
      buildTypes {
          release {                                                                                      
              isMinifyEnabled = false                       
              proguardFiles(getDefaultProguardFile("proguard-android-optimize.txt"),
  "proguard-rules.pro")                                                                                  
          }
      }                                                                                                  
      compileOptions {                                      
          sourceCompatibility = JavaVersion.VERSION_11
          targetCompatibility = JavaVersion.VERSION_11
      }
      kotlinOptions { jvmTarget = "11" }
      buildFeatures { compose = true }                                                                   
      testOptions { unitTests { isReturnDefaultValues = true } }
  }                                                                                                      
                                                            
  ksp {                                                                                                  
      arg("room.schemaLocation", "$projectDir/schemas")     
      arg("room.incremental", "true")
      arg("room.expandProjection", "true")
  }                                                                                                      
   
  dependencies {                                                                                         
      implementation(libs.androidx.core.ktx)                
      implementation(libs.androidx.lifecycle.runtime.ktx)
      implementation(libs.androidx.lifecycle.viewmodel.compose)
      implementation(libs.androidx.lifecycle.runtime.compose)                                            
      implementation(libs.androidx.activity.compose)
      implementation(platform(libs.androidx.compose.bom))                                                
      implementation(libs.androidx.ui)                                                                   
      implementation(libs.androidx.ui.graphics)
      implementation(libs.androidx.ui.tooling.preview)                                                   
      implementation(libs.androidx.material3)               
      implementation(libs.androidx.material.icons)                                                       
      implementation(libs.navigation.compose)
      implementation(libs.hilt.android)                                                                  
      ksp(libs.hilt.android.compiler)                       
      implementation(libs.hilt.navigation.compose)                                                       
      implementation(libs.hilt.work)
      ksp(libs.hilt.compiler)                                                                            
      implementation(libs.room.runtime)                     
      implementation(libs.room.ktx)
      ksp(libs.room.compiler)                                                                            
      implementation(libs.work.runtime.ktx)
      implementation(libs.coil.compose)                                                                  
      implementation(libs.kotlinx.coroutines.android)       
      implementation(libs.gson)                                                                          
      implementation(libs.security.crypto)
      debugImplementation(libs.androidx.ui.tooling)                                                      
      debugImplementation(libs.androidx.ui.test.manifest)   
      testImplementation(libs.junit)                                                                     
      testImplementation(libs.mockito.core)
      testImplementation(libs.mockito.kotlin)                                                            
      testImplementation(libs.kotlinx.coroutines.test)      
      testImplementation(libs.arch.core.testing)                                                         
      testImplementation(libs.turbine)
      androidTestImplementation(libs.androidx.junit)                                                     
      androidTestImplementation(libs.androidx.espresso.core)
      androidTestImplementation(platform(libs.androidx.compose.bom))                                     
      androidTestImplementation(libs.androidx.ui.test.junit4)
  }                                                                                                      
                                                                                                         
  ---
                                                                                                         
  Now create ALL of the following files with EXACTLY this content:

  === AndroidManifest.xml ===                                                                            
  <?xml version="1.0" encoding="utf-8"?>
  <manifest xmlns:android="http://schemas.android.com/apk/res/android"                                   
      xmlns:tools="http://schemas.android.com/tools">       
      <uses-permission android:name="android.permission.INTERNET" />                                     
      <uses-permission android:name="android.permission.ACCESS_NETWORK_STATE" />
      <uses-permission android:name="android.permission.CAMERA" />                                       
      <uses-permission android:name="android.permission.READ_MEDIA_IMAGES" android:minSdkVersion="33" />
      <uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE" android:maxSdkVersion="32"
   />                                                                                                    
      <uses-feature android:name="android.hardware.camera" android:required="false" />                   
      <application                                                                                       
          android:name=".MarketplaceApplication"            
          android:allowBackup="true"                                                                     
          android:dataExtractionRules="@xml/data_extraction_rules"
          android:fullBackupContent="@xml/backup_rules"                                                  
          android:icon="@mipmap/ic_launcher"                                                             
          android:label="@string/app_name"
          android:roundIcon="@mipmap/ic_launcher_round"                                                  
          android:supportsRtl="true"                        
          android:theme="@style/Theme.MarketPlace"                                                       
          tools:targetApi="31">
          <activity android:name=".MainActivity" android:exported="true"                                 
              android:label="@string/app_name" android:theme="@style/Theme.MarketPlace">                 
              <intent-filter>
                  <action android:name="android.intent.action.MAIN" />                                   
                  <category android:name="android.intent.category.LAUNCHER" />                           
              </intent-filter>
          </activity>                                                                                    
          <provider android:name="androidx.core.content.FileProvider"
              android:authorities="${applicationId}.fileprovider"                                        
              android:exported="false" android:grantUriPermissions="true">
              <meta-data android:name="android.support.FILE_PROVIDER_PATHS"                              
                  android:resource="@xml/file_paths" />                                                  
          </provider>
          <provider android:name="androidx.startup.InitializationProvider"                               
              android:authorities="${applicationId}.androidx-startup"                                    
              android:exported="false" tools:node="merge">
              <meta-data android:name="androidx.work.WorkManagerInitializer"                             
                  android:value="androidx.startup" tools:node="remove" />
          </provider>                                                                                    
      </application>                                        
  </manifest>                                                                                            
                                                            
  === res/xml/file_paths.xml ===
  <?xml version="1.0" encoding="utf-8"?>
  <paths xmlns:android="http://schemas.android.com/apk/res/android">                                     
      <external-files-path name="marketplace_images" path="Pictures/" />
      <cache-path name="marketplace_cache" path="images/" />                                             
  </paths>                                                  
                                                                                                         
  === res/values/strings.xml ===                            
  <resources>
      <string name="app_name">MarketPlace</string>
  </resources>                                                                                           
   
  === res/values/themes.xml ===                                                                          
  <?xml version="1.0" encoding="utf-8"?>                    
  <resources>
      <style name="Theme.MarketPlace" parent="android:Theme.Material.Light.NoActionBar" />
  </resources>                                                                                           
   
  === res/xml/backup_rules.xml ===                                                                       
  <?xml version="1.0" encoding="utf-8"?>                    
  <full-backup-content></full-backup-content>                                                            
   
  === res/xml/data_extraction_rules.xml ===                                                              
  <?xml version="1.0" encoding="utf-8"?>                    
  <data-extraction-rules>                                                                                
      <cloud-backup></cloud-backup>
  </data-extraction-rules>                                                                               
                                                            
  ---

  Now create all Kotlin source files:                                                                    
   
  === MarketplaceApplication.kt ===                                                                      
  package com.example.marketplace                           

  import android.app.Application
  import androidx.hilt.work.HiltWorkerFactory
  import androidx.work.Configuration                                                                     
  import coil.ImageLoader
  import coil.ImageLoaderFactory                                                                         
  import coil.disk.DiskCache                                
  import coil.memory.MemoryCache
  import coil.request.CachePolicy
  import dagger.hilt.android.HiltAndroidApp                                                              
  import okio.Path.Companion.toOkioPath
  import javax.inject.Inject                                                                             
                                                            
  @HiltAndroidApp                                                                                        
  class MarketplaceApplication : Application(), Configuration.Provider, ImageLoaderFactory {
      @Inject lateinit var workerFactory: HiltWorkerFactory
                                                                                                         
      override val workManagerConfiguration: Configuration
          get() = Configuration.Builder()                                                                
              .setWorkerFactory(workerFactory)                                                           
              .setMinimumLoggingLevel(android.util.Log.INFO)
              .build()                                                                                   
                                                                                                         
      override fun newImageLoader(): ImageLoader = ImageLoader.Builder(this)
          .memoryCache { MemoryCache.Builder(this).maxSizePercent(0.20).build() }                        
          .diskCache {                                                                                   
              DiskCache.Builder()
                  .directory(cacheDir.resolve("image_cache").toOkioPath())                               
                  .maxSizeBytes(100L * 1024 * 1024)                                                      
                  .build()
          }                                                                                              
          .diskCachePolicy(CachePolicy.ENABLED)             
          .memoryCachePolicy(CachePolicy.ENABLED)                                                        
          .crossfade(true)                                  
          .build()                                                                                       
  }
                                                                                                         
  === MainActivity.kt ===                                   
  package com.example.marketplace

  import android.os.Bundle
  import androidx.activity.ComponentActivity
  import androidx.activity.compose.setContent
  import androidx.activity.enableEdgeToEdge                                                              
  import com.example.marketplace.navigation.MarketplaceNavGraph
  import com.example.marketplace.sync.SyncWorker                                                         
  import com.example.marketplace.ui.theme.MarketPlaceTheme                                               
  import dagger.hilt.android.AndroidEntryPoint
                                                                                                         
  @AndroidEntryPoint                                        
  class MainActivity : ComponentActivity() {
      override fun onCreate(savedInstanceState: Bundle?) {                                               
          super.onCreate(savedInstanceState)
          enableEdgeToEdge()                                                                             
          SyncWorker.enqueue(this)                          
          setContent {
              MarketPlaceTheme {                                                                         
                  MarketplaceNavGraph()
              }                                                                                          
          }                                                 
      }
  }

  === domain/model/Listing.kt ===
  package com.example.marketplace.domain.model
                                                                                                         
  data class Listing(
      val id: String,                                                                                    
      val title: String,                                    
      val description: String,
      val price: Double,
      val imageUrl: String?,
      val sellerId: String,                                                                              
      val sellerName: String,
      val createdAt: Long,                                                                               
      val updatedAt: Long,                                  
      val isFavorite: Boolean = false,                                                                   
      val syncStatus: SyncStatus = SyncStatus.SYNCED
  )                                                                                                      
                                                            
  enum class SyncStatus { SYNCED, PENDING_SYNC, SYNC_FAILED }                                            
  enum class SyncOperation { CREATE, UPDATE, DELETE }
                                                                                                         
  data class SyncInfo(                                                                                   
      val pendingCount: Int = 0,
      val isSyncing: Boolean = false,                                                                    
      val lastSyncedAt: Long? = null,                       
      val lastError: String? = null                                                                      
  )
                                                                                                         
  === domain/repository/ListingRepository.kt ===            
  package com.example.marketplace.domain.repository
                                                                                                         
  import com.example.marketplace.domain.model.Listing
  import com.example.marketplace.domain.model.SyncInfo                                                   
  import kotlinx.coroutines.flow.Flow                       

  interface ListingRepository {
      fun getListings(): Flow<List<Listing>>
      fun getFavoriteListings(): Flow<List<Listing>>                                                     
      suspend fun getListingById(id: String): Listing?
      suspend fun refreshListings(): Result<Unit>                                                        
      suspend fun createListing(listing: Listing): Result<Listing>                                       
      suspend fun updateListing(listing: Listing): Result<Listing>
      suspend fun toggleFavorite(listingId: String): Result<Unit>                                        
      suspend fun syncPendingItems(): Result<Int>           
      fun observeSyncInfo(): Flow<SyncInfo>                                                              
  }                                                         
                                                                                                         
  === domain/usecase/GetListingsUseCase.kt ===                                                           
  package com.example.marketplace.domain.usecase
                                                                                                         
  import com.example.marketplace.domain.model.Listing       
  import com.example.marketplace.domain.repository.ListingRepository
  import kotlinx.coroutines.flow.Flow                                                                    
  import javax.inject.Inject
                                                                                                         
  class GetListingsUseCase @Inject constructor(private val repository: ListingRepository) {              
      operator fun invoke(): Flow<List<Listing>> = repository.getListings()
  }                                                                                                      
                                                            
  === domain/usecase/GetFavoritesUseCase.kt ===                                                          
  package com.example.marketplace.domain.usecase
                                                                                                         
  import com.example.marketplace.domain.model.Listing       
  import com.example.marketplace.domain.repository.ListingRepository
  import kotlinx.coroutines.flow.Flow
  import javax.inject.Inject                                                                             
   
  class GetFavoritesUseCase @Inject constructor(private val repository: ListingRepository) {             
      operator fun invoke(): Flow<List<Listing>> = repository.getFavoriteListings()
  }                                                                                                      
   
  === domain/usecase/CreateListingUseCase.kt ===                                                         
  package com.example.marketplace.domain.usecase            

  import com.example.marketplace.domain.model.Listing
  import com.example.marketplace.domain.repository.ListingRepository
  import javax.inject.Inject                                                                             
   
  class CreateListingUseCase @Inject constructor(private val repository: ListingRepository) {            
      suspend operator fun invoke(listing: Listing): Result<Listing> = repository.createListing(listing)
  }                                                                                                      
   
  === domain/usecase/ToggleFavoriteUseCase.kt ===                                                        
  package com.example.marketplace.domain.usecase            

  import com.example.marketplace.domain.repository.ListingRepository                                     
  import javax.inject.Inject
                                                                                                         
  class ToggleFavoriteUseCase @Inject constructor(private val repository: ListingRepository) {
      suspend operator fun invoke(listingId: String): Result<Unit> = repository.toggleFavorite(listingId)
  }                                                                                                      
   
  === domain/usecase/SyncPendingUseCase.kt ===                                                           
  package com.example.marketplace.domain.usecase            

  import com.example.marketplace.domain.repository.ListingRepository                                     
  import javax.inject.Inject
                                                                                                         
  class SyncPendingUseCase @Inject constructor(private val repository: ListingRepository) {
      suspend operator fun invoke(): Result<Int> = repository.syncPendingItems()
  }                                                                                                      
   
  === data/local/entity/ListingEntity.kt ===                                                             
  package com.example.marketplace.data.local.entity         

  import androidx.room.Entity
  import androidx.room.PrimaryKey
                                                                                                         
  @Entity(tableName = "listings")
  data class ListingEntity(                                                                              
      @PrimaryKey val id: String,                           
      val title: String,
      val description: String,
      val price: Double,
      val imageUrl: String?,                                                                             
      val sellerId: String,
      val sellerName: String,                                                                            
      val createdAt: Long,                                  
      val updatedAt: Long,
      val syncStatus: String
  )                                                                                                      
   
  === data/local/entity/FavoriteEntity.kt ===                                                            
  package com.example.marketplace.data.local.entity         

  import androidx.room.Entity
  import androidx.room.PrimaryKey
                                                                                                         
  @Entity(tableName = "favorites")
  data class FavoriteEntity(                                                                             
      @PrimaryKey val listingId: String,                    
      val createdAt: Long = System.currentTimeMillis()
  )                                                                                                      
   
  === data/local/entity/SyncQueueEntity.kt ===                                                           
  package com.example.marketplace.data.local.entity         

  import androidx.room.Entity
  import androidx.room.PrimaryKey

  @Entity(tableName = "sync_queue")                                                                      
  data class SyncQueueEntity(
      @PrimaryKey(autoGenerate = true) val id: Long = 0,                                                 
      val listingId: String,                                
      val operation: String,
      val payload: String,                                                                               
      val createdAt: Long = System.currentTimeMillis(),
      val retryCount: Int = 0                                                                            
  )                                                         

  === data/local/dao/ListingDao.kt ===                                                                   
  package com.example.marketplace.data.local.dao
                                                                                                         
  import androidx.room.*                                    
  import com.example.marketplace.data.local.entity.ListingEntity
  import kotlinx.coroutines.flow.Flow
                                                                                                         
  @Dao
  interface ListingDao {                                                                                 
      @Query("SELECT * FROM listings ORDER BY updatedAt DESC")
      fun observeAll(): Flow<List<ListingEntity>>
                                                                                                         
      @Query("SELECT l.* FROM listings l INNER JOIN favorites f ON l.id = f.listingId ORDER BY           
  f.createdAt DESC")                                                                                     
      fun observeFavorites(): Flow<List<ListingEntity>>                                                  
                                                            
      @Query("SELECT * FROM listings WHERE id = :id LIMIT 1")
      suspend fun getById(id: String): ListingEntity?
                                                                                                         
      @Insert(onConflict = OnConflictStrategy.REPLACE)
      suspend fun insertAll(listings: List<ListingEntity>)                                               
                                                                                                         
      @Insert(onConflict = OnConflictStrategy.REPLACE)
      suspend fun insert(listing: ListingEntity)                                                         
                                                            
      @Update
      suspend fun update(listing: ListingEntity)

      @Query("UPDATE listings SET syncStatus = :status WHERE id = :id")                                  
      suspend fun updateSyncStatus(id: String, status: String)
                                                                                                         
      @Query("DELETE FROM listings WHERE id = :id")         
      suspend fun deleteById(id: String)
                                                                                                         
      @Query("SELECT COUNT(*) FROM listings WHERE syncStatus = 'PENDING_SYNC' OR syncStatus =            
  'SYNC_FAILED'")                                                                                        
      fun observePendingCount(): Flow<Int>                                                               
  }                                                         

  === data/local/dao/FavoriteDao.kt ===
  package com.example.marketplace.data.local.dao
                                                                                                         
  import androidx.room.*
  import com.example.marketplace.data.local.entity.FavoriteEntity                                        
  import kotlinx.coroutines.flow.Flow                       

  @Dao
  interface FavoriteDao {
      @Query("SELECT listingId FROM favorites")                                                          
      fun observeFavoriteIds(): Flow<List<String>>
                                                                                                         
      @Query("SELECT listingId FROM favorites")                                                          
      suspend fun getAllFavoriteIds(): List<String>
                                                                                                         
      @Query("SELECT EXISTS(SELECT 1 FROM favorites WHERE listingId = :listingId)")
      suspend fun isFavorite(listingId: String): Boolean
                                                                                                         
      @Insert(onConflict = OnConflictStrategy.REPLACE)
      suspend fun insert(favorite: FavoriteEntity)                                                       
                                                            
      @Query("DELETE FROM favorites WHERE listingId = :listingId")                                       
      suspend fun deleteById(listingId: String)
  }                                                                                                      
                                                            
  === data/local/dao/SyncQueueDao.kt ===
  package com.example.marketplace.data.local.dao

  import androidx.room.*                                                                                 
  import com.example.marketplace.data.local.entity.SyncQueueEntity
  import kotlinx.coroutines.flow.Flow                                                                    
                                                            
  @Dao
  interface SyncQueueDao {
      @Query("SELECT * FROM sync_queue ORDER BY createdAt ASC")
      suspend fun getAll(): List<SyncQueueEntity>                                                        
   
      @Query("SELECT COUNT(*) FROM sync_queue")                                                          
      fun observeCount(): Flow<Int>                         
                                                                                                         
      @Insert(onConflict = OnConflictStrategy.REPLACE)
      suspend fun insert(item: SyncQueueEntity)                                                          
                                                            
      @Query("DELETE FROM sync_queue WHERE id = :id")                                                    
      suspend fun deleteById(id: Long)
                                                                                                         
      @Query("UPDATE sync_queue SET retryCount = retryCount + 1 WHERE id = :id")                         
      suspend fun incrementRetry(id: Long)
                                                                                                         
      @Query("DELETE FROM sync_queue WHERE listingId = :listingId")                                      
      suspend fun deleteByListingId(listingId: String)
  }                                                                                                      
                                                            
  === data/local/database/MarketplaceDatabase.kt ===
  package com.example.marketplace.data.local.database
                                                                                                         
  import androidx.room.Database
  import androidx.room.RoomDatabase                                                                      
  import com.example.marketplace.data.local.dao.FavoriteDao 
  import com.example.marketplace.data.local.dao.ListingDao
  import com.example.marketplace.data.local.dao.SyncQueueDao                                             
  import com.example.marketplace.data.local.entity.FavoriteEntity
  import com.example.marketplace.data.local.entity.ListingEntity                                         
  import com.example.marketplace.data.local.entity.SyncQueueEntity                                       
   
  @Database(                                                                                             
      entities = [ListingEntity::class, FavoriteEntity::class, SyncQueueEntity::class],
      version = 2,                                                                                       
      exportSchema = true
  )                                                                                                      
  abstract class MarketplaceDatabase : RoomDatabase() {     
      abstract fun listingDao(): ListingDao
      abstract fun favoriteDao(): FavoriteDao
      abstract fun syncQueueDao(): SyncQueueDao                                                          
      companion object { const val DATABASE_NAME = "marketplace.db" }
  }                                                                                                      
                                                            
  === data/remote/api/MarketplaceApiService.kt ===                                                       
  package com.example.marketplace.data.remote.api           

  import com.example.marketplace.data.remote.dto.ApiResponse                                             
  import com.example.marketplace.data.remote.dto.CreateListingRequest
  import com.example.marketplace.data.remote.dto.ListingDto                                              
                                                                                                         
  interface MarketplaceApiService {
      suspend fun getListings(): ApiResponse<List<ListingDto>>                                           
      suspend fun getListing(id: String): ApiResponse<ListingDto>
      suspend fun createListing(request: CreateListingRequest): ApiResponse<ListingDto>                  
      suspend fun updateListing(id: String, request: CreateListingRequest): ApiResponse<ListingDto>
      suspend fun deleteListing(id: String): ApiResponse<Unit>                                           
  }                                                                                                      
   
  === data/remote/dto/ListingDto.kt ===                                                                  
  package com.example.marketplace.data.remote.dto           

  data class ListingDto(                                                                                 
      val id: String,
      val title: String,                                                                                 
      val description: String,                              
      val price: Double,
      val imageUrl: String?,
      val sellerId: String,
      val sellerName: String,
      val createdAt: Long,                                                                               
      val updatedAt: Long
  )                                                                                                      
                                                            
  data class CreateListingRequest(
      val id: String,
      val title: String,
      val description: String,                                                                           
      val price: Double,
      val imageUrl: String?,                                                                             
      val sellerId: String,                                 
      val sellerName: String,
      val createdAt: Long,
      val updatedAt: Long                                                                                
  )
                                                                                                         
  data class ApiResponse<T>(val data: T?, val error: String?, val success: Boolean)                      
   
  === data/remote/mock/MockMarketplaceApiService.kt ===                                                  
  package com.example.marketplace.data.remote.mock          

  import com.example.marketplace.data.remote.api.MarketplaceApiService                                   
  import com.example.marketplace.data.remote.dto.ApiResponse
  import com.example.marketplace.data.remote.dto.CreateListingRequest                                    
  import com.example.marketplace.data.remote.dto.ListingDto                                              
  import kotlinx.coroutines.delay
  import javax.inject.Inject                                                                             
  import javax.inject.Singleton                             
                                                                                                         
  @Singleton
  class MockMarketplaceApiService @Inject constructor() : MarketplaceApiService {                        
                                                            
      private val serverListings = mutableListOf<ListingDto>().apply { addAll(seedListings()) }          
   
      override suspend fun getListings(): ApiResponse<List<ListingDto>> {                                
          delay(600)                                        
          return ApiResponse(data = serverListings.toList(), error = null, success = true)               
      }                                                     
                                                                                                         
      override suspend fun getListing(id: String): ApiResponse<ListingDto> {
          delay(300)                                                                                     
          val listing = serverListings.find { it.id == id } 
          return if (listing != null) ApiResponse(data = listing, error = null, success = true)
          else ApiResponse(data = null, error = "Listing not found", success = false)                    
      }
                                                                                                         
      override suspend fun createListing(request: CreateListingRequest): ApiResponse<ListingDto> {       
          delay(800)
          val dto = ListingDto(                                                                          
              id = request.id, title = request.title, description = request.description,
              price = request.price,                                                                     
              imageUrl = request.imageUrl ?: "https://picsum.photos/seed/${request.id}/400/300",
              sellerId = request.sellerId, sellerName = request.sellerName,                              
              createdAt = request.createdAt, updatedAt = System.currentTimeMillis()
          )                                                                                              
          serverListings.add(dto)                           
          return ApiResponse(data = dto, error = null, success = true)                                   
      }
                                                                                                         
      override suspend fun updateListing(id: String, request: CreateListingRequest):
  ApiResponse<ListingDto> {
          delay(600)
          val index = serverListings.indexOfFirst { it.id == id }                                        
          return if (index >= 0) {
              if (request.updatedAt >= serverListings[index].updatedAt) {                                
                  val updated = serverListings[index].copy(                                              
                      title = request.title, description = request.description,
                      price = request.price,                                                             
                      imageUrl = request.imageUrl ?: serverListings[index].imageUrl,                     
                      updatedAt = System.currentTimeMillis()
                  )                                                                                      
                  serverListings[index] = updated           
                  ApiResponse(data = updated, error = null, success = true)                              
              } else {
                  ApiResponse(data = serverListings[index], error = null, success = true)                
              }                                                                                          
          } else {
              ApiResponse(data = null, error = "Listing not found", success = false)                     
          }                                                 
      }

      override suspend fun deleteListing(id: String): ApiResponse<Unit> {                                
          delay(400)
          serverListings.removeIf { it.id == id }                                                        
          return ApiResponse(data = null, error = null, success = true)
      }

      private fun seedListings(): List<ListingDto> {                                                     
          val now = System.currentTimeMillis()
          val names = listOf("Alice M.", "Bob K.", "Carol J.", "Dave R.", "Eva S.")                      
          fun make(id: String, title: String, desc: String, price: Double, offset: Long) = ListingDto(   
              id = id, title = title, description = desc, price = price,                                 
              imageUrl = "https://picsum.photos/seed/$id/400/300",                                       
              sellerId = "seller_$id", sellerName = names.random(),                                      
              createdAt = now - offset, updatedAt = now - offset                                         
          )
          return listOf(                                                                                 
              make("1","iPhone 15 Pro","Excellent condition, 1 year old. Comes with original             
  box.",850.0,86400000L),                                                                                
              make("2","Mountain Bike Trek X1","Professional grade 21-speed mountain bike, barely        
  used.",420.0,172800000L),                                                                              
              make("3","IKEA Kallax Shelf","4x4 cube shelf in white, great for
  storage.",80.0,259200000L),                                                                            
              make("4","Canon EOS R50","Mirrorless camera kit with 18-45mm lens, 500 shutter
  count.",650.0,345600000L),                                                                             
              make("5","Vintage Levi's 501","Classic 501 jeans, size 32x30, excellent vintage
  condition.",95.0,432000000L),                                                                          
              make("6","Toyota Prius 2019","Low mileage hybrid, 45k miles, one owner, full service
  history.",18500.0,518400000L),                                                                         
              make("7","Leather Sofa 3-Seater","Brown genuine leather, very comfortable, minor wear on
  armrests.",350.0,604800000L),                                                                          
              make("8","MacBook Air M2","13-inch, 8GB RAM, 256GB SSD, Space Gray, 8 months
  old.",900.0,691200000L),                                                                               
              make("9","PlayStation 5 Bundle","PS5 disc edition with 3 games and extra
  controller.",480.0,777600000L),                                                                        
              make("10","Acoustic Guitar Yamaha","Yamaha F310 acoustic guitar, perfect for
  beginners.",120.0,864000000L),                                                                         
              make("11","Nike Air Max 90","Men's size 10, worn twice, white colorway.",85.0,950400000L),
              make("12","Garden Shed 6x4","Metal garden shed, easy assembly, all parts                   
  included.",195.0,1036800000L),                                                                         
              make("13","Harry Potter Complete Set","All 7 books, hardcover UK first editions, good      
  condition.",140.0,1123200000L),                                                                        
              make("14","LEGO Technic Bugatti","42151, sealed box, never opened.",220.0,1209600000L),
              make("15","Gold Necklace 18K","18K gold chain, 45cm, hallmarked, comes with                
  certificate.",310.0,1296000000L),                                                                      
              make("16","Samsung 4K TV 55\"","QLED 55 inch, Smart TV, excellent picture                  
  quality.",520.0,1382400000L),                                                                          
              make("17","Road Bike Specialized","Carbon frame road bike, Shimano 105 groupset,
  56cm.",780.0,1468800000L),                                                                             
              make("18","Coffee Table Oak","Solid oak coffee table with storage shelf, great
  condition.",145.0,1555200000L),                                                                        
              make("19","Vintage Rolex Watch","Submariner circa 1985, fully serviced, keeps accurate
  time.",4200.0,1641600000L),                                                                            
              make("20","Drone DJI Mini 3","DJI Mini 3 Pro, 2 batteries, ND filter set, carry
  case.",390.0,1728000000L)                                                                              
          )                                                 
      }                                                                                                  
  }                                                         

  === data/repository/ListingRepositoryImpl.kt ===                                                       
  package com.example.marketplace.data.repository
                                                                                                         
  import com.example.marketplace.data.local.dao.FavoriteDao 
  import com.example.marketplace.data.local.dao.ListingDao
  import com.example.marketplace.data.local.dao.SyncQueueDao                                             
  import com.example.marketplace.data.local.entity.FavoriteEntity
  import com.example.marketplace.data.local.entity.SyncQueueEntity                                       
  import com.example.marketplace.data.remote.api.MarketplaceApiService                                   
  import com.example.marketplace.domain.model.Listing
  import com.example.marketplace.domain.model.SyncInfo                                                   
  import com.example.marketplace.domain.model.SyncOperation                                              
  import com.example.marketplace.domain.model.SyncStatus
  import com.example.marketplace.domain.repository.ListingRepository                                     
  import com.example.marketplace.util.toCreateRequest       
  import com.example.marketplace.util.toDomain                                                           
  import com.example.marketplace.util.toEntity                                                           
  import com.google.gson.Gson
  import kotlinx.coroutines.flow.Flow                                                                    
  import kotlinx.coroutines.flow.combine                                                                 
  import kotlinx.coroutines.flow.map
  import javax.inject.Inject                                                                             
  import javax.inject.Singleton                             
                                                                                                         
  @Singleton
  class ListingRepositoryImpl @Inject constructor(                                                       
      private val listingDao: ListingDao,                   
      private val favoriteDao: FavoriteDao,
      private val syncQueueDao: SyncQueueDao,
      private val apiService: MarketplaceApiService,                                                     
      private val gson: Gson
  ) : ListingRepository {                                                                                
                                                            
      override fun getListings(): Flow<List<Listing>> =                                                  
          combine(listingDao.observeAll(), favoriteDao.observeFavoriteIds()) { listings, favorites ->
              val favoriteSet = favorites.toHashSet()                                                    
              listings.map { it.toDomain(isFavorite = it.id in favoriteSet) }                            
          }                                                                                              
                                                                                                         
      override fun getFavoriteListings(): Flow<List<Listing>> =                                          
          listingDao.observeFavorites().map { list -> list.map { it.toDomain(isFavorite = true) } }
                                                                                                         
      override suspend fun getListingById(id: String): Listing? {                                        
          val entity = listingDao.getById(id) ?: return null                                             
          return entity.toDomain(isFavorite = favoriteDao.isFavorite(id))                                
      }                                                                                                  
   
      override suspend fun refreshListings(): Result<Unit> = runCatching {                               
          val response = apiService.getListings()           
          if (!response.success || response.data == null) error(response.error ?: "Failed to fetch
  listings")                                                                                             
          val toInsert = response.data.map { remote ->
              val local = listingDao.getById(remote.id)                                                  
              if (local != null && local.updatedAt > remote.updatedAt) local else remote.toEntity()
          }                                                                                              
          listingDao.insertAll(toInsert)                    
      }                                                                                                  
                                                            
      override suspend fun createListing(listing: Listing): Result<Listing> = runCatching {              
          val pendingListing = listing.copy(syncStatus = SyncStatus.PENDING_SYNC)
          listingDao.insert(pendingListing.toEntity())                                                   
          syncQueueDao.insert(SyncQueueEntity(
              listingId = listing.id,                                                                    
              operation = SyncOperation.CREATE.name,        
              payload = gson.toJson(listing.toCreateRequest())                                           
          ))                                                
          pendingListing
      }                                                                                                  
   
      override suspend fun updateListing(listing: Listing): Result<Listing> = runCatching {              
          val updated = listing.copy(updatedAt = System.currentTimeMillis(), syncStatus =
  SyncStatus.PENDING_SYNC)                                                                               
          listingDao.update(updated.toEntity())
          syncQueueDao.insert(SyncQueueEntity(                                                           
              listingId = listing.id,                       
              operation = SyncOperation.UPDATE.name,                                                     
              payload = gson.toJson(updated.toCreateRequest())
          ))                                                                                             
          updated                                           
      }

      override suspend fun toggleFavorite(listingId: String): Result<Unit> = runCatching {               
          if (favoriteDao.isFavorite(listingId)) favoriteDao.deleteById(listingId)
          else favoriteDao.insert(FavoriteEntity(listingId = listingId))                                 
      }                                                     
                                                                                                         
      override suspend fun syncPendingItems(): Result<Int> = runCatching {
          val queue = syncQueueDao.getAll()
          var successCount = 0                                                                           
          for (item in queue) {
              runCatching {                                                                              
                  val request = gson.fromJson(item.payload, 
  com.example.marketplace.data.remote.dto.CreateListingRequest::class.java)                              
                  val response = when (SyncOperation.valueOf(item.operation)) {
                      SyncOperation.CREATE -> apiService.createListing(request)                          
                      SyncOperation.UPDATE -> apiService.updateListing(item.listingId, request)
                      SyncOperation.DELETE -> {                                                          
                          apiService.deleteListing(item.listingId).also {
                              if (it.success) listingDao.deleteById(item.listingId)                      
                          }                                 
                          syncQueueDao.deleteById(item.id)                                               
                          successCount++                                                                 
                          return@runCatching
                      }                                                                                  
                  }                                         
                  if (response.success && response.data != null) {
                      val local = listingDao.getById(item.listingId)                                     
                      if (local != null) {
                          val resolved = if (response.data.updatedAt >= local.updatedAt)                 
  response.data.toEntity()                                                                               
                                         else local.copy(syncStatus = SyncStatus.SYNCED.name)
                          listingDao.insert(resolved)                                                    
                      }                                     
                      syncQueueDao.deleteById(item.id)                                                   
                      successCount++                        
                  } else {
                      syncQueueDao.incrementRetry(item.id)                                               
                      if (item.retryCount >= MAX_RETRIES) {
                          listingDao.updateSyncStatus(item.listingId, SyncStatus.SYNC_FAILED.name)       
                          syncQueueDao.deleteById(item.id)  
                      }                                                                                  
                  }                                         
              }.onFailure {                                                                              
                  syncQueueDao.incrementRetry(item.id)      
                  listingDao.updateSyncStatus(item.listingId, SyncStatus.SYNC_FAILED.name)               
              }
          }                                                                                              
          successCount                                      
      }

      override fun observeSyncInfo(): Flow<SyncInfo> =                                                   
          combine(listingDao.observePendingCount(), syncQueueDao.observeCount()) { _, queued ->
              SyncInfo(pendingCount = queued, isSyncing = false)                                         
          }                                                 
                                                                                                         
      private companion object { const val MAX_RETRIES = 3 }                                             
  }
                                                                                                         
  === util/Mappers.kt ===                                   
  package com.example.marketplace.util
                                                                                                         
  import com.example.marketplace.data.local.entity.ListingEntity
  import com.example.marketplace.data.remote.dto.CreateListingRequest                                    
  import com.example.marketplace.data.remote.dto.ListingDto 
  import com.example.marketplace.domain.model.Listing                                                    
  import com.example.marketplace.domain.model.SyncStatus
                                                                                                         
  fun ListingEntity.toDomain(isFavorite: Boolean = false) = Listing(                                     
      id = id, title = title, description = description, price = price,
      imageUrl = imageUrl, sellerId = sellerId, sellerName = sellerName,                                 
      createdAt = createdAt, updatedAt = updatedAt,                                                      
      isFavorite = isFavorite, syncStatus = SyncStatus.valueOf(syncStatus)
  )                                                                                                      
                                                                                                         
  fun Listing.toEntity() = ListingEntity(
      id = id, title = title, description = description, price = price,                                  
      imageUrl = imageUrl, sellerId = sellerId, sellerName = sellerName,
      createdAt = createdAt, updatedAt = updatedAt, syncStatus = syncStatus.name
  )                                                                                                      
   
  fun ListingDto.toEntity() = ListingEntity(                                                             
      id = id, title = title, description = description, price = price,
      imageUrl = imageUrl, sellerId = sellerId, sellerName = sellerName,                                 
      createdAt = createdAt, updatedAt = updatedAt, syncStatus = SyncStatus.SYNCED.name
  )                                                                                                      
                                                            
  fun ListingDto.toDomain() = Listing(                                                                   
      id = id, title = title, description = description, price = price,
      imageUrl = imageUrl, sellerId = sellerId, sellerName = sellerName,                                 
      createdAt = createdAt, updatedAt = updatedAt,
      isFavorite = false, syncStatus = SyncStatus.SYNCED                                                 
  )                                                                                                      
   
  fun Listing.toCreateRequest() = CreateListingRequest(                                                  
      id = id, title = title, description = description, price = price,
      imageUrl = imageUrl, sellerId = sellerId, sellerName = sellerName,                                 
      createdAt = createdAt, updatedAt = updatedAt
  )                                                                                                      
                                                            
  === util/InputValidator.kt ===                                                                         
  package com.example.marketplace.util
                                                                                                         
  object InputValidator {                                   
      fun validateTitle(title: String): String? {
          if (title.isBlank()) return "Title is required"                                                
          if (title.length < 3) return "Title must be at least 3 characters"
          if (title.length > 100) return "Title must be under 100 characters"                            
          return null                                                                                    
      }
      fun validateDescription(description: String): String? {                                            
          if (description.isBlank()) return "Description is required"
          if (description.length < 10) return "Description must be at least 10 characters"               
          if (description.length > 2000) return "Description must be under 2000 characters"
          return null                                                                                    
      }                                                     
      fun validatePrice(priceText: String): String? {                                                    
          if (priceText.isBlank()) return "Price is required"
          val price = priceText.toDoubleOrNull() ?: return "Enter a valid price"
          if (price <= 0) return "Price must be greater than 0"                                          
          if (price > 1_000_000) return "Price must be under \$1,000,000"
          return null                                                                                    
      }                                                     
      data class ListingValidation(val titleError: String?, val descriptionError: String?, val           
  priceError: String?) {                                                                                 
          val isValid get() = titleError == null && descriptionError == null && priceError == null
      }                                                                                                  
      fun validateListing(title: String, description: String, price: String) = ListingValidation(
          titleError = validateTitle(title),                                                             
          descriptionError = validateDescription(description),
          priceError = validatePrice(price)                                                              
      )                                                     
  }
                                                                                                         
  === util/SecureStorageManager.kt ===
  package com.example.marketplace.util                                                                   
                                                            
  import android.content.Context
  import androidx.security.crypto.EncryptedSharedPreferences
  import androidx.security.crypto.MasterKey                                                              
  import dagger.hilt.android.qualifiers.ApplicationContext
  import javax.inject.Inject                                                                             
  import javax.inject.Singleton                             

  @Singleton
  class SecureStorageManager @Inject constructor(@ApplicationContext private val context: Context) {
      private val masterKey =                                                                            
  MasterKey.Builder(context).setKeyScheme(MasterKey.KeyScheme.AES256_GCM).build()                        
      private val prefs = EncryptedSharedPreferences.create(                                             
          context, "secure_prefs", masterKey,                                                            
          EncryptedSharedPreferences.PrefKeyEncryptionScheme.AES256_SIV,                                 
          EncryptedSharedPreferences.PrefValueEncryptionScheme.AES256_GCM
      )                                                                                                  
      fun getUserId(): String = prefs.getString(KEY_USER_ID, DEFAULT_USER_ID) ?: DEFAULT_USER_ID
      fun getUserName(): String = prefs.getString(KEY_USER_NAME, DEFAULT_USER_NAME) ?: DEFAULT_USER_NAME 
      companion object {                                    
          private const val KEY_USER_ID = "user_id"                                                      
          private const val KEY_USER_NAME = "user_name"                                                  
          const val DEFAULT_USER_ID = "demo_user_001"
          const val DEFAULT_USER_NAME = "Demo User"                                                      
      }                                                     
  }                                                                                                      
                                                            
  === util/ImageUtils.kt ===
  package com.example.marketplace.util
                                                                                                         
  import android.content.Context
  import android.graphics.Bitmap                                                                         
  import android.graphics.BitmapFactory                     
  import android.net.Uri
  import android.os.Environment
  import androidx.core.content.FileProvider
  import java.io.File                                                                                    
  import java.io.FileOutputStream
  import java.text.SimpleDateFormat                                                                      
  import java.util.Date                                     
  import java.util.Locale

  object ImageUtils {
      fun createImageFile(context: Context): File {
          val timestamp = SimpleDateFormat("yyyyMMdd_HHmmss", Locale.getDefault()).format(Date())        
          val dir = context.getExternalFilesDir(Environment.DIRECTORY_PICTURES)                          
          return File.createTempFile("LISTING_${timestamp}_", ".jpg", dir)                               
      }                                                                                                  
      fun getUriForFile(context: Context, file: File): Uri =
          FileProvider.getUriForFile(context, "${context.packageName}.fileprovider", file)               
      fun copyAndResizeImage(context: Context, sourceUri: Uri, destFile: File): Boolean {
          return try {                                                                                   
              val inputStream = context.contentResolver.openInputStream(sourceUri) ?: return false
              val original = BitmapFactory.decodeStream(inputStream)                                     
              inputStream.close()                           
              val maxWidth = 800                                                                         
              val scaled = if (original.width > maxWidth) {                                              
                  val ratio = maxWidth.toFloat() / original.width
                  Bitmap.createScaledBitmap(original, maxWidth, (original.height * ratio).toInt(), true) 
              } else original                                                                            
              FileOutputStream(destFile).use { out -> scaled.compress(Bitmap.CompressFormat.JPEG, 85,
  out) }                                                                                                 
              if (scaled !== original) scaled.recycle()     
              original.recycle()                                                                         
              true                                          
          } catch (e: Exception) { false }
      }                                                                                                  
  }
                                                                                                         
  === di/AppModule.kt ===                                   
  package com.example.marketplace.di

  import com.example.marketplace.data.remote.api.MarketplaceApiService                                   
  import com.example.marketplace.data.remote.mock.MockMarketplaceApiService
  import com.google.gson.Gson                                                                            
  import dagger.Binds                                       
  import dagger.Module                                                                                   
  import dagger.Provides
  import dagger.hilt.InstallIn                                                                           
  import dagger.hilt.components.SingletonComponent          
  import javax.inject.Singleton

  @Module
  @InstallIn(SingletonComponent::class)
  abstract class AppModule {                                                                             
      @Binds @Singleton
      abstract fun bindApiService(mock: MockMarketplaceApiService): MarketplaceApiService                
      companion object {                                                                                 
          @Provides @Singleton
          fun provideGson(): Gson = Gson()                                                               
      }                                                     
  }

  === di/DatabaseModule.kt ===
  package com.example.marketplace.di
                                                                                                         
  import android.content.Context
  import androidx.room.Room                                                                              
  import com.example.marketplace.data.local.dao.FavoriteDao 
  import com.example.marketplace.data.local.dao.ListingDao
  import com.example.marketplace.data.local.dao.SyncQueueDao                                             
  import com.example.marketplace.data.local.database.MarketplaceDatabase
  import dagger.Module                                                                                   
  import dagger.Provides                                                                                 
  import dagger.hilt.InstallIn
  import dagger.hilt.android.qualifiers.ApplicationContext                                               
  import dagger.hilt.components.SingletonComponent          
  import javax.inject.Singleton
                                                                                                         
  @Module
  @InstallIn(SingletonComponent::class)                                                                  
  object DatabaseModule {                                   
      @Provides @Singleton
      fun provideDatabase(@ApplicationContext context: Context): MarketplaceDatabase =
          Room.databaseBuilder(context, MarketplaceDatabase::class.java,                                 
  MarketplaceDatabase.DATABASE_NAME)
              .fallbackToDestructiveMigration()                                                          
              .build()                                                                                   
      @Provides fun provideListingDao(db: MarketplaceDatabase): ListingDao = db.listingDao()
      @Provides fun provideFavoriteDao(db: MarketplaceDatabase): FavoriteDao = db.favoriteDao()          
      @Provides fun provideSyncQueueDao(db: MarketplaceDatabase): SyncQueueDao = db.syncQueueDao()       
  }                                                                                                      
                                                                                                         
  === di/RepositoryModule.kt ===                                                                         
  package com.example.marketplace.di                        

  import com.example.marketplace.data.repository.ListingRepositoryImpl
  import com.example.marketplace.domain.repository.ListingRepository
  import dagger.Binds                                                                                    
  import dagger.Module
  import dagger.hilt.InstallIn                                                                           
  import dagger.hilt.components.SingletonComponent          
  import javax.inject.Singleton
                                                                                                         
  @Module
  @InstallIn(SingletonComponent::class)                                                                  
  abstract class RepositoryModule {                         
      @Binds @Singleton
      abstract fun bindListingRepository(impl: ListingRepositoryImpl): ListingRepository
  }                                                                                                      
   
  === di/SyncModule.kt ===                                                                               
  package com.example.marketplace.di                        

  import com.example.marketplace.sync.ConnectivityObserver                                               
  import com.example.marketplace.sync.NetworkConnectivityObserver
  import dagger.Binds                                                                                    
  import dagger.Module                                      
  import dagger.hilt.InstallIn
  import dagger.hilt.components.SingletonComponent
  import javax.inject.Singleton                                                                          
   
  @Module                                                                                                
  @InstallIn(SingletonComponent::class)                     
  abstract class SyncModule {
      @Binds @Singleton
      abstract fun bindConnectivityObserver(impl: NetworkConnectivityObserver): ConnectivityObserver
  }                                                                                                      
   
  === sync/ConnectivityObserver.kt ===                                                                   
  package com.example.marketplace.sync                      

  import kotlinx.coroutines.flow.Flow                                                                    
   
  interface ConnectivityObserver {                                                                       
      fun observe(): Flow<NetworkStatus>                    
      fun isCurrentlyConnected(): Boolean
  }                                                                                                      
   
  enum class NetworkStatus { Available, Unavailable, Losing, Lost }                                      
                                                            
  === sync/NetworkConnectivityObserver.kt ===                                                            
  package com.example.marketplace.sync
                                                                                                         
  import android.content.Context                            
  import android.net.ConnectivityManager
  import android.net.Network
  import android.net.NetworkCapabilities                                                                 
  import android.net.NetworkRequest
  import dagger.hilt.android.qualifiers.ApplicationContext                                               
  import kotlinx.coroutines.channels.awaitClose             
  import kotlinx.coroutines.flow.Flow                                                                    
  import kotlinx.coroutines.flow.callbackFlow
  import kotlinx.coroutines.flow.distinctUntilChanged                                                    
  import javax.inject.Inject                                
  import javax.inject.Singleton
                                                                                                         
  @Singleton
  class NetworkConnectivityObserver @Inject constructor(                                                 
      @ApplicationContext private val context: Context      
  ) : ConnectivityObserver {
      private val connectivityManager = context.getSystemService(Context.CONNECTIVITY_SERVICE) as
  ConnectivityManager                                                                                    
   
      override fun observe(): Flow<NetworkStatus> = callbackFlow {                                       
          val callback = object : ConnectivityManager.NetworkCallback() {
              override fun onAvailable(network: Network) { trySend(NetworkStatus.Available) }
              override fun onLosing(network: Network, maxMsToLive: Int) { trySend(NetworkStatus.Losing) }
              override fun onLost(network: Network) { trySend(NetworkStatus.Lost) }                      
              override fun onUnavailable() { trySend(NetworkStatus.Unavailable) }                        
          }                                                                                              
          val request =                                     
  NetworkRequest.Builder().addCapability(NetworkCapabilities.NET_CAPABILITY_INTERNET).build()            
          connectivityManager.registerNetworkCallback(request, callback)
          trySend(if (isCurrentlyConnected()) NetworkStatus.Available else NetworkStatus.Unavailable)    
          awaitClose { connectivityManager.unregisterNetworkCallback(callback) }
      }.distinctUntilChanged()                                                                           
                                                            
      override fun isCurrentlyConnected(): Boolean {                                                     
          val network = connectivityManager.activeNetwork ?: return false
          val caps = connectivityManager.getNetworkCapabilities(network) ?: return false                 
          return caps.hasCapability(NetworkCapabilities.NET_CAPABILITY_INTERNET) &&
                 caps.hasCapability(NetworkCapabilities.NET_CAPABILITY_VALIDATED)                        
      }                                                     
  }                                                                                                      
                                                            
  === sync/SyncWorker.kt ===
  package com.example.marketplace.sync
                                                                                                         
  import android.content.Context
  import androidx.hilt.work.HiltWorker                                                                   
  import androidx.work.*                                    
  import com.example.marketplace.domain.repository.ListingRepository
  import dagger.assisted.Assisted                                                                        
  import dagger.assisted.AssistedInject
                                                                                                         
  @HiltWorker                                               
  class SyncWorker @AssistedInject constructor(
      @Assisted context: Context,
      @Assisted params: WorkerParameters,                                                                
      private val repository: ListingRepository
  ) : CoroutineWorker(context, params) {                                                                 
                                                            
      override suspend fun doWork(): Result {                                                            
          return try {
              repository.refreshListings()                                                               
              val synced = repository.syncPendingItems()    
              if (synced.isSuccess) Result.success() else Result.retry()
          } catch (e: Exception) {                                                                       
              if (runAttemptCount < MAX_ATTEMPTS) Result.retry() else Result.failure()
          }                                                                                              
      }                                                     
                                                                                                         
      companion object {                                    
          const val WORK_NAME = "marketplace_sync"
          private const val MAX_ATTEMPTS = 3                                                             
          fun enqueue(context: Context) {
              val constraints =                                                                          
  Constraints.Builder().setRequiredNetworkType(NetworkType.CONNECTED).build()
              val request = OneTimeWorkRequestBuilder<SyncWorker>().setConstraints(constraints).build()  
              WorkManager.getInstance(context).enqueueUniqueWork(WORK_NAME, ExistingWorkPolicy.KEEP,     
  request)
          }                                                                                              
      }                                                     
  }

  === navigation/Screen.kt ===                                                                           
  package com.example.marketplace.navigation
                                                                                                         
  sealed class Screen(val route: String) {                  
      data object Listings : Screen("listings")
      data object CreateListing : Screen("create_listing")                                               
  }
                                                                                                         
  === navigation/MarketplaceNavGraph.kt ===                                                              
  package com.example.marketplace.navigation
                                                                                                         
  import androidx.compose.runtime.Composable                
  import androidx.navigation.compose.NavHost
  import androidx.navigation.compose.composable
  import androidx.navigation.compose.rememberNavController
  import com.example.marketplace.presentation.create.CreateListingScreen                                 
  import com.example.marketplace.presentation.listings.ListingsScreen
                                                                                                         
  @Composable                                               
  fun MarketplaceNavGraph() {
      val navController = rememberNavController()                                                        
      NavHost(navController = navController, startDestination = Screen.Listings.route) {
          composable(Screen.Listings.route) {                                                            
              ListingsScreen(onCreateClick = { navController.navigate(Screen.CreateListing.route) })     
          }
          composable(Screen.CreateListing.route) {                                                       
              CreateListingScreen(onNavigateBack = { navController.popBackStack() })                     
          }
      }                                                                                                  
  }                                                         

  === presentation/components/ListingCard.kt ===                                                         
  package com.example.marketplace.presentation.components
                                                                                                         
  import androidx.compose.foundation.layout.*               
  import androidx.compose.material.icons.Icons
  import androidx.compose.material.icons.filled.*
  import androidx.compose.material3.*                                                                    
  import androidx.compose.runtime.Composable
  import androidx.compose.ui.Alignment                                                                   
  import androidx.compose.ui.Modifier                       
  import androidx.compose.ui.graphics.Color
  import androidx.compose.ui.layout.ContentScale
  import androidx.compose.ui.text.font.FontWeight                                                        
  import androidx.compose.ui.text.style.TextOverflow
  import androidx.compose.ui.unit.dp                                                                     
  import coil.compose.AsyncImage                            
  import com.example.marketplace.domain.model.Listing                                                    
  import com.example.marketplace.domain.model.SyncStatus
  import java.text.NumberFormat                                                                          
  import java.util.Locale                                   
                                                                                                         
  @Composable
  fun ListingCard(listing: Listing, onFavoriteClick: () -> Unit, modifier: Modifier = Modifier) {        
      Card(modifier = modifier.fillMaxWidth(), elevation = CardDefaults.cardElevation(defaultElevation =
  2.dp)) {                                                                                               
          Column {
              Box {                                                                                      
                  AsyncImage(                               
                      model = listing.imageUrl,                                                          
                      contentDescription = listing.title,   
                      modifier = Modifier.fillMaxWidth().aspectRatio(4f / 3f),
                      contentScale = ContentScale.Crop                                                   
                  )
                  if (listing.syncStatus != SyncStatus.SYNCED) {                                         
                      Icon(                                                                              
                          imageVector = if (listing.syncStatus == SyncStatus.PENDING_SYNC)
  Icons.Default.Schedule else Icons.Default.SyncProblem,                                                 
                          contentDescription = listing.syncStatus.name,
                          tint = Color.White,                                                            
                          modifier = Modifier.padding(8.dp).size(18.dp).align(Alignment.TopStart)
                      )                                                                                  
                  }                                         
                  IconButton(onClick = onFavoriteClick, modifier = Modifier.align(Alignment.TopEnd)) {   
                      Icon(                                                                              
                          imageVector = if (listing.isFavorite) Icons.Default.Favorite else
  Icons.Default.FavoriteBorder,                                                                          
                          contentDescription = if (listing.isFavorite) "Remove from favorites" else "Add
  to favorites",                                                                                         
                          tint = if (listing.isFavorite) Color.Red else Color.White
                      )                                                                                  
                  }                                         
              }                                                                                          
              Column(modifier = Modifier.padding(12.dp), verticalArrangement =
  Arrangement.spacedBy(4.dp)) {                                                                          
                  Row(modifier = Modifier.fillMaxWidth(), horizontalArrangement =
  Arrangement.SpaceBetween, verticalAlignment = Alignment.CenterVertically) {                            
                      Text(text = listing.title, style = MaterialTheme.typography.titleSmall, fontWeight
  = FontWeight.SemiBold, maxLines = 1, overflow = TextOverflow.Ellipsis, modifier = Modifier.weight(1f)) 
                      Text(text = NumberFormat.getCurrencyInstance(Locale.US).format(listing.price),
  style = MaterialTheme.typography.titleSmall, fontWeight = FontWeight.Bold, color =                     
  MaterialTheme.colorScheme.primary)                        
                  }                                                                                      
                  Text(text = listing.description, style = MaterialTheme.typography.bodySmall, maxLines =
   2, overflow = TextOverflow.Ellipsis, color = MaterialTheme.colorScheme.onSurfaceVariant)              
                  Text(text = listing.sellerName, style = MaterialTheme.typography.labelSmall, color =
  MaterialTheme.colorScheme.secondary)                                                                   
              }                                             
          }                                                                                              
      }                                                     
  }

  === presentation/components/SyncStatusBanner.kt ===                                                    
  package com.example.marketplace.presentation.components
                                                                                                         
  import androidx.compose.animation.AnimatedVisibility      
  import androidx.compose.animation.fadeIn
  import androidx.compose.animation.fadeOut                                                              
  import androidx.compose.foundation.background
  import androidx.compose.foundation.layout.*                                                            
  import androidx.compose.material.icons.Icons              
  import androidx.compose.material.icons.filled.CloudOff
  import androidx.compose.material.icons.filled.Sync                                                     
  import androidx.compose.material.icons.filled.SyncProblem
  import androidx.compose.material3.*                                                                    
  import androidx.compose.runtime.Composable                                                             
  import androidx.compose.ui.Alignment
  import androidx.compose.ui.Modifier                                                                    
  import androidx.compose.ui.unit.dp                        
  import com.example.marketplace.domain.model.SyncInfo
                                                                                                         
  @Composable
  fun SyncStatusBanner(isOnline: Boolean, syncInfo: SyncInfo, modifier: Modifier = Modifier) {           
      val showOffline = !isOnline                                                                        
      val showPending = isOnline && syncInfo.pendingCount > 0
      val showSyncing = isOnline && syncInfo.isSyncing                                                   
      AnimatedVisibility(visible = showOffline || showPending || showSyncing, enter = fadeIn(), exit =   
  fadeOut(), modifier = modifier) {                                                                      
          val (icon, message, bgColor) = when {                                                          
              showOffline -> Triple(Icons.Default.CloudOff,                                              
                  if (syncInfo.pendingCount > 0) "Offline — ${syncInfo.pendingCount} item(s) pending
  sync" else "You are offline",                                                                          
                  MaterialTheme.colorScheme.errorContainer) 
              showSyncing -> Triple(Icons.Default.Sync, "Syncing…",                                      
  MaterialTheme.colorScheme.primaryContainer)                                                            
              else -> Triple(Icons.Default.SyncProblem, "${syncInfo.pendingCount} item(s) waiting to
  sync", MaterialTheme.colorScheme.secondaryContainer)                                                   
          }                                                 
          Row(modifier = Modifier.fillMaxWidth().background(bgColor).padding(horizontal = 16.dp, vertical
   = 8.dp),                                                                                              
              verticalAlignment = Alignment.CenterVertically, horizontalArrangement =
  Arrangement.spacedBy(8.dp)) {                                                                          
              Icon(imageVector = icon, contentDescription = null, modifier = Modifier.size(16.dp), tint =
   MaterialTheme.colorScheme.onSurface)                                                                  
              Text(text = message, style = MaterialTheme.typography.labelMedium, color =
  MaterialTheme.colorScheme.onSurface)                                                                   
          }                                                 
      }                                                                                                  
  }                                                         

  === presentation/listings/ListingsUiState.kt ===
  package com.example.marketplace.presentation.listings

  import com.example.marketplace.domain.model.Listing                                                    
  import com.example.marketplace.domain.model.SyncInfo
                                                                                                         
  data class ListingsUiState(                               
      val listings: List<Listing> = emptyList(),
      val isLoading: Boolean = false,
      val isRefreshing: Boolean = false,                                                                 
      val isSyncing: Boolean = false,
      val error: String? = null,                                                                         
      val syncInfo: SyncInfo = SyncInfo(),                  
      val isOnline: Boolean = true                                                                       
  )
                                                                                                         
  === presentation/listings/ListingsViewModel.kt ===        
  package com.example.marketplace.presentation.listings
                                                                                                         
  import androidx.lifecycle.ViewModel
  import androidx.lifecycle.viewModelScope                                                               
  import com.example.marketplace.domain.repository.ListingRepository
  import com.example.marketplace.domain.usecase.GetListingsUseCase
  import com.example.marketplace.domain.usecase.ToggleFavoriteUseCase                                    
  import com.example.marketplace.sync.ConnectivityObserver
  import com.example.marketplace.sync.NetworkStatus                                                      
  import dagger.hilt.android.lifecycle.HiltViewModel        
  import kotlinx.coroutines.flow.*                                                                       
  import kotlinx.coroutines.launch                                                                       
  import javax.inject.Inject
                                                                                                         
  @HiltViewModel                                            
  class ListingsViewModel @Inject constructor(
      private val getListingsUseCase: GetListingsUseCase,
      private val toggleFavoriteUseCase: ToggleFavoriteUseCase,                                          
      private val repository: ListingRepository,
      private val connectivityObserver: ConnectivityObserver                                             
  ) : ViewModel() {                                         
                                                                                                         
      private val _uiState = MutableStateFlow(ListingsUiState(isLoading = true))
      val uiState: StateFlow<ListingsUiState> = _uiState.asStateFlow()                                   
                                                                                                         
      init {
          getListingsUseCase().onEach { listings -> _uiState.update { it.copy(listings = listings,       
  isLoading = false) } }.launchIn(viewModelScope)                                                        
          repository.observeSyncInfo().onEach { syncInfo -> _uiState.update { it.copy(syncInfo =
  syncInfo) } }.launchIn(viewModelScope)                                                                 
          connectivityObserver.observe().onEach { status -> _uiState.update { it.copy(isOnline = status
  == NetworkStatus.Available) } }.launchIn(viewModelScope)                                               
          refresh()                                         
      }                                                                                                  
                                                            
      fun refresh() {
          viewModelScope.launch {
              _uiState.update { it.copy(isRefreshing = true, error = null) }                             
              val result = repository.refreshListings()
              _uiState.update { it.copy(isRefreshing = false, error = result.exceptionOrNull()?.message) 
  }                                                         
          }                                                                                              
      }                                                     
                                                                                                         
      fun sync() {
          viewModelScope.launch {                                                                        
              _uiState.update { it.copy(isSyncing = true) } 
              repository.syncPendingItems()
              repository.refreshListings()                                                               
              _uiState.update { it.copy(isSyncing = false) }
          }                                                                                              
      }                                                     

      fun toggleFavorite(listingId: String) {                                                            
          viewModelScope.launch { toggleFavoriteUseCase(listingId) }
      }                                                                                                  
                                                            
      fun dismissError() { _uiState.update { it.copy(error = null) } }                                   
  }
                                                                                                         
  === presentation/listings/ListingsScreen.kt ===           
  package com.example.marketplace.presentation.listings

  import androidx.compose.foundation.layout.*
  import androidx.compose.foundation.lazy.grid.*
  import androidx.compose.material.icons.Icons                                                           
  import androidx.compose.material.icons.filled.Add
  import androidx.compose.material.icons.filled.Favorite                                                 
  import androidx.compose.material.icons.filled.Sync                                                     
  import androidx.compose.material3.*
  import androidx.compose.material3.pulltorefresh.PullToRefreshBox                                       
  import androidx.compose.runtime.*                                                                      
  import androidx.compose.ui.Alignment
  import androidx.compose.ui.Modifier                                                                    
  import androidx.compose.ui.unit.dp                        
  import androidx.hilt.navigation.compose.hiltViewModel                                                  
  import androidx.lifecycle.compose.collectAsStateWithLifecycle
  import com.example.marketplace.presentation.components.ListingCard                                     
  import com.example.marketplace.presentation.components.SyncStatusBanner
  import com.example.marketplace.presentation.favorites.FavoritesContent                                 
    
  @OptIn(ExperimentalMaterial3Api::class)                                                                
  @Composable                                               
  fun ListingsScreen(onCreateClick: () -> Unit, viewModel: ListingsViewModel = hiltViewModel()) {
      val uiState by viewModel.uiState.collectAsStateWithLifecycle()                                     
      val snackbarHostState = remember { SnackbarHostState() }
      var showFavorites by remember { mutableStateOf(false) }                                            
      val sheetState = rememberModalBottomSheetState(skipPartiallyExpanded = true)
                                                                                                         
      LaunchedEffect(uiState.error) {                                                                    
          uiState.error?.let { snackbarHostState.showSnackbar(it); viewModel.dismissError() }            
      }                                                                                                  
                                         
      Scaffold(
          topBar = {
              Column {
                  TopAppBar(                                                                             
                      title = { Text("Marketplace") },
                      actions = {                                                                        
                          IconButton(onClick = { showFavorites = true }) {
                              Icon(Icons.Default.Favorite, contentDescription = "Favorites", tint =      
  MaterialTheme.colorScheme.primary)
                          }                                                                              
                          IconButton(onClick = viewModel::sync, enabled = !uiState.isSyncing) {
                              if (uiState.isSyncing) CircularProgressIndicator(modifier =                
  Modifier.size(20.dp), strokeWidth = 2.dp)                                                              
                              else Icon(Icons.Default.Sync, contentDescription = "Sync")                 
                          }                                                                              
                      }                  
                  )                                                                                      
                  SyncStatusBanner(isOnline = uiState.isOnline, syncInfo = uiState.syncInfo)
              }
          },
          floatingActionButton = {
              FloatingActionButton(onClick = onCreateClick) {                                            
                  Icon(Icons.Default.Add, contentDescription = "Create listing")
              }                                                                                          
          },                             
          snackbarHost = { SnackbarHost(snackbarHostState) }
      ) { padding ->                                                                                     
          when {     
              uiState.isLoading -> Box(modifier = Modifier.fillMaxSize().padding(padding),               
  contentAlignment = Alignment.Center) { CircularProgressIndicator() }                                   
              else -> PullToRefreshBox(isRefreshing = uiState.isRefreshing, onRefresh =
  viewModel::refresh, modifier = Modifier.fillMaxSize().padding(padding)) {                              
                  if (uiState.listings.isEmpty()) {
                      Box(modifier = Modifier.fillMaxSize(), contentAlignment = Alignment.Center) {      
                          Text("No listings yet. Create one!", style =                                   
  MaterialTheme.typography.bodyLarge, color = MaterialTheme.colorScheme.onSurfaceVariant)                
                      }                                                                                  
                  } else {                                                                               
                      LazyVerticalGrid(columns = GridCells.Adaptive(minSize = 160.dp), contentPadding =
  PaddingValues(12.dp), horizontalArrangement = Arrangement.spacedBy(12.dp), verticalArrangement =       
  Arrangement.spacedBy(12.dp)) { 
                          items(items = uiState.listings, key = { it.id }) { listing ->                  
                              ListingCard(listing = listing, onFavoriteClick = {
  viewModel.toggleFavorite(listing.id) })                                                                
                          }      
                      }                                                                                  
                  }                      
              }
          }
      }

      if (showFavorites) {
          ModalBottomSheet(onDismissRequest = { showFavorites = false }, sheetState = sheetState,
  modifier = Modifier.fillMaxWidth()) {                                                                  
              FavoritesContent()      
          }                                                                                              
      }                                  
  }

  === presentation/favorites/FavoritesViewModel.kt ===
  package com.example.marketplace.presentation.favorites
                                                                                                         
  import androidx.lifecycle.ViewModel   
  import androidx.lifecycle.viewModelScope                                                               
  import com.example.marketplace.domain.model.Listing
  import com.example.marketplace.domain.usecase.GetFavoritesUseCase
  import com.example.marketplace.domain.usecase.ToggleFavoriteUseCase                                    
  import dagger.hilt.android.lifecycle.HiltViewModel
  import kotlinx.coroutines.flow.*                                                                       
  import kotlinx.coroutines.launch                                                                       
  import javax.inject.Inject               
                                                                                                         
  @HiltViewModel                         
  class FavoritesViewModel @Inject constructor(
      private val getFavoritesUseCase: GetFavoritesUseCase,
      private val toggleFavoriteUseCase: ToggleFavoriteUseCase                                           
  ) : ViewModel() {                         
      private val _favorites = MutableStateFlow<List<Listing>>(emptyList())                              
      val favorites: StateFlow<List<Listing>> = _favorites.asStateFlow()                                 
                                              
      init {                                                                                             
          getFavoritesUseCase().onEach { list -> _favorites.update { list } }.launchIn(viewModelScope)
      }                                                                                                  
                                              
      fun removeFavorite(listingId: String) {                                                            
          viewModelScope.launch { toggleFavoriteUseCase(listingId) }
      }                                                                                                  
  }                                           
                                                                                                         
  === presentation/favorites/FavoritesScreen.kt ===
  package com.example.marketplace.presentation.favorites

  import androidx.compose.foundation.layout.*
  import androidx.compose.foundation.lazy.grid.*
  import androidx.compose.material3.MaterialTheme                                                        
  import androidx.compose.material3.Text     
  import androidx.compose.runtime.*                                                                      
  import androidx.compose.ui.Alignment                                                                   
  import androidx.compose.ui.Modifier        
  import androidx.compose.ui.text.font.FontWeight                                                        
  import androidx.compose.ui.unit.dp     
  import androidx.hilt.navigation.compose.hiltViewModel
  import androidx.lifecycle.compose.collectAsStateWithLifecycle                                          
  import com.example.marketplace.presentation.components.ListingCard
                                                                                                         
  @Composable                            
  fun FavoritesContent(viewModel: FavoritesViewModel = hiltViewModel()) {
      val favorites by viewModel.favorites.collectAsStateWithLifecycle()                                 
                                             
      Text(text = "Favorites", style = MaterialTheme.typography.titleLarge, fontWeight = FontWeight.Bold,
          modifier = Modifier.fillMaxWidth().padding(horizontal = 16.dp, vertical = 8.dp))
                                                                                                         
      if (favorites.isEmpty()) {             
          Box(modifier = Modifier.fillMaxSize().padding(32.dp), contentAlignment = Alignment.Center) {   
              Text("No favorites yet.\nTap the heart icon on any listing.", style =                      
  MaterialTheme.typography.bodyLarge, color = MaterialTheme.colorScheme.onSurfaceVariant)                
          }                                                                                              
      } else {                                                                                           
          LazyVerticalGrid(columns = GridCells.Adaptive(minSize = 160.dp), contentPadding =
  PaddingValues(12.dp),                                                                                  
              horizontalArrangement = Arrangement.spacedBy(12.dp), verticalArrangement =               
  Arrangement.spacedBy(12.dp)) {                                                                         
              items(items = favorites, key = { it.id }) { listing ->                                   
                  ListingCard(listing = listing, onFavoriteClick = { viewModel.removeFavorite(listing.id)
   })                                                       
              }                                                                                          
          }                                                 
      }
  }                                                                                                    
                                                                                                         
  === presentation/create/CreateListingUiState.kt ===
  package com.example.marketplace.presentation.create                                                    
                                                            
  data class CreateListingUiState(
      val title: String = "",                                                                          
      val description: String = "",                                                                      
      val price: String = "",     
      val localImagePath: String? = null,                                                                
      val titleError: String? = null,                       
      val descriptionError: String? = null,                                                            
      val priceError: String? = null,                                                                    
      val isSubmitting: Boolean = false,
      val isSuccess: Boolean = false,                                                                    
      val submitError: String? = null                                                                  
  ) {                                                                                                    
      val hasAnyError get() = titleError != null || descriptionError != null || priceError != null
  }                                                                                                      
                                                                                                       
  === presentation/create/CreateListingViewModel.kt ===                                                  
  package com.example.marketplace.presentation.create
                                                                                                         
  import androidx.lifecycle.ViewModel                                                                  
  import androidx.lifecycle.viewModelScope                                                               
  import com.example.marketplace.domain.model.Listing
  import com.example.marketplace.domain.model.SyncStatus                                                 
  import com.example.marketplace.domain.usecase.CreateListingUseCase
  import com.example.marketplace.util.InputValidator                                                   
  import com.example.marketplace.util.SecureStorageManager                                               
  import dagger.hilt.android.lifecycle.HiltViewModel
  import kotlinx.coroutines.flow.*                                                                       
  import kotlinx.coroutines.launch                                                                       
  import java.util.UUID           
  import javax.inject.Inject                                                                             
                                                                                                       
  @HiltViewModel                                                                                         
  class CreateListingViewModel @Inject constructor(
      private val createListingUseCase: CreateListingUseCase,                                            
      private val secureStorageManager: SecureStorageManager
  ) : ViewModel() {
      private val _uiState = MutableStateFlow(CreateListingUiState())                                  
      val uiState: StateFlow<CreateListingUiState> = _uiState.asStateFlow()                              
                                  
      fun updateTitle(value: String) { _uiState.update { it.copy(title = value, titleError = null) } }   
      fun updateDescription(value: String) { _uiState.update { it.copy(description = value,              
  descriptionError = null) } }                                                                           
      fun updatePrice(value: String) { _uiState.update { it.copy(price = value, priceError = null) } }   
      fun updateImagePath(path: String?) { _uiState.update { it.copy(localImagePath = path) } }          
                                                                                                       
      fun submit() {                                                                                     
          val state = _uiState.value                                                                     
          val validation = InputValidator.validateListing(state.title, state.description, state.price)   
          if (!validation.isValid) {                                                                     
              _uiState.update { it.copy(titleError = validation.titleError, descriptionError =         
  validation.descriptionError, priceError = validation.priceError) }                                     
              return                                                                                   
          }                                                                                              
          viewModelScope.launch {                           
              _uiState.update { it.copy(isSubmitting = true, submitError = null) }                       
              val now = System.currentTimeMillis()          
              val listing = Listing(                                                                   
                  id = UUID.randomUUID().toString(), title = state.title.trim(),                         
                  description = state.description.trim(), price = state.price.toDouble(),
                  imageUrl = null, sellerId = secureStorageManager.getUserId(),                          
                  sellerName = secureStorageManager.getUserName(),                                       
                  createdAt = now, updatedAt = now, syncStatus = SyncStatus.PENDING_SYNC               
              )                                                                                          
              val result = createListingUseCase(listing)                                               
              _uiState.update { st ->                                                                    
                  if (result.isSuccess) st.copy(isSubmitting = false, isSuccess = true)
                  else st.copy(isSubmitting = false, submitError = result.exceptionOrNull()?.message ?:  
  "Failed to save listing")                                                                              
              }                                                                                        
          }                                                                                              
      }                                                     
                                                                                                         
      fun dismissError() { _uiState.update { it.copy(submitError = null) } }
  }                                                                                                    
                                                                                                         
  === presentation/create/CreateListingScreen.kt ===
  package com.example.marketplace.presentation.create                                                    
                                                            
  import android.net.Uri
  import androidx.activity.compose.rememberLauncherForActivityResult                                   
  import androidx.activity.result.contract.ActivityResultContracts                                       
  import androidx.compose.foundation.background
  import androidx.compose.foundation.border                                                              
  import androidx.compose.foundation.clickable              
  import androidx.compose.foundation.layout.*                                                          
  import androidx.compose.foundation.rememberScrollState                                                 
  import androidx.compose.foundation.shape.RoundedCornerShape
  import androidx.compose.foundation.text.KeyboardOptions                                                
  import androidx.compose.foundation.verticalScroll                                                    
  import androidx.compose.material.icons.Icons                                                           
  import androidx.compose.material.icons.automirrored.filled.ArrowBack
  import androidx.compose.material.icons.filled.AddAPhoto                                                
  import androidx.compose.material.icons.filled.CameraAlt                                              
  import androidx.compose.material.icons.filled.PhotoLibrary                                             
  import androidx.compose.material3.*
  import androidx.compose.runtime.*                                                                      
  import androidx.compose.ui.Alignment                                                                   
  import androidx.compose.ui.Modifier
  import androidx.compose.ui.draw.clip                                                                   
  import androidx.compose.ui.layout.ContentScale                                                       
  import androidx.compose.ui.platform.LocalContext                                                       
  import androidx.compose.ui.text.input.KeyboardType
  import androidx.compose.ui.unit.dp                                                                     
  import androidx.hilt.navigation.compose.hiltViewModel                                                
  import androidx.lifecycle.compose.collectAsStateWithLifecycle                                          
  import coil.compose.AsyncImage  
  import com.example.marketplace.util.ImageUtils                                                         
                                                                                                       
  @OptIn(ExperimentalMaterial3Api::class)                                                                
  @Composable                     
  fun CreateListingScreen(onNavigateBack: () -> Unit, viewModel: CreateListingViewModel =                
  hiltViewModel()) {                                                                                   
      val uiState by viewModel.uiState.collectAsStateWithLifecycle()                                     
      val context = LocalContext.current
      var showImageSheet by remember { mutableStateOf(false) }                                           
      var cameraImageFile by remember { mutableStateOf<java.io.File?>(null) }                          
                                                                                                         
      LaunchedEffect(uiState.isSuccess) { if (uiState.isSuccess) onNavigateBack() }                    
                                                                                                         
      val cameraLauncher = rememberLauncherForActivityResult(ActivityResultContracts.TakePicture()) {    
  success ->                                                                                             
          if (success) cameraImageFile?.let { viewModel.updateImagePath(it.absolutePath) }               
      }                                                     
      val galleryLauncher = rememberLauncherForActivityResult(ActivityResultContracts.PickVisualMedia()) 
  { uri: Uri? ->                                                                                       
          uri?.let {                                                                                     
              val destFile = ImageUtils.createImageFile(context)
              if (ImageUtils.copyAndResizeImage(context, it, destFile))                                  
  viewModel.updateImagePath(destFile.absolutePath)                                                       
          }                                                                                            
      }                                                                                                  
                                                            
      Scaffold(                                                                                          
          topBar = {                                        
              TopAppBar(title = { Text("New Listing") }, navigationIcon = {
                  IconButton(onClick = onNavigateBack) { Icon(Icons.AutoMirrored.Filled.ArrowBack,
  contentDescription = "Back") }                                                                       
              })                                                                                         
          }                                                                                              
      ) { padding ->                                                                                     
          Column(modifier =                                                                              
  Modifier.fillMaxSize().padding(padding).verticalScroll(rememberScrollState()).padding(16.dp),
  verticalArrangement = Arrangement.spacedBy(16.dp)) {                                                 
              Box(modifier = Modifier.fillMaxWidth().height(180.dp).clip(RoundedCornerShape(12.dp))      
                  .background(MaterialTheme.colorScheme.surfaceVariant)
                  .border(1.dp, MaterialTheme.colorScheme.outline, RoundedCornerShape(12.dp))            
                  .clickable { showImageSheet = true }, contentAlignment = Alignment.Center) {           
                  if (uiState.localImagePath != null) {                                                  
                      AsyncImage(model = uiState.localImagePath, contentDescription = "Selected image",  
  modifier = Modifier.fillMaxSize(), contentScale = ContentScale.Crop)                                   
                  } else {                                                                             
                      Column(horizontalAlignment = Alignment.CenterHorizontally) {                       
                          Icon(Icons.Default.AddAPhoto, contentDescription = null, modifier =
  Modifier.size(40.dp), tint = MaterialTheme.colorScheme.onSurfaceVariant)                               
                          Spacer(modifier = Modifier.height(8.dp))                                     
                          Text("Tap to add a photo", style = MaterialTheme.typography.bodyMedium, color =
   MaterialTheme.colorScheme.onSurfaceVariant)                                                         
                      }                                                                                  
                  }                                                                                      
              }                                                                                          
              OutlinedTextField(value = uiState.title, onValueChange = viewModel::updateTitle, label = { 
  Text("Title *") }, isError = uiState.titleError != null, supportingText = uiState.titleError?.let { {
  Text(it) } }, modifier = Modifier.fillMaxWidth(), singleLine = true)                                 
              OutlinedTextField(value = uiState.description, onValueChange =                             
  viewModel::updateDescription, label = { Text("Description *") }, isError = uiState.descriptionError !=
  null, supportingText = uiState.descriptionError?.let { { Text(it) } }, modifier =                      
  Modifier.fillMaxWidth(), minLines = 3, maxLines = 6)                                                   
              OutlinedTextField(value = uiState.price, onValueChange = viewModel::updatePrice, label = {
  Text("Price (USD) *") }, isError = uiState.priceError != null, supportingText = uiState.priceError?.let
   { { Text(it) } }, modifier = Modifier.fillMaxWidth(), singleLine = true, keyboardOptions =          
  KeyboardOptions(keyboardType = KeyboardType.Decimal), prefix = { Text("$") })                          
              uiState.submitError?.let { Text(text = it, color = MaterialTheme.colorScheme.error, style =
   MaterialTheme.typography.bodySmall) }                                                                 
              Spacer(modifier = Modifier.height(8.dp))                                                 
              Button(onClick = viewModel::submit, modifier = Modifier.fillMaxWidth(), enabled =          
  !uiState.isSubmitting) {                                                                             
                  if (uiState.isSubmitting) CircularProgressIndicator(modifier = Modifier.size(20.dp),   
  strokeWidth = 2.dp)                                                                                    
                  else Text("Post Listing")                                                              
              }                                                                                          
          }                                                 
      }                                                                                                
                                                                                                         
      if (showImageSheet) {       
          ModalBottomSheet(onDismissRequest = { showImageSheet = false }) {                              
              Column(modifier = Modifier.fillMaxWidth().padding(16.dp), verticalArrangement =
  Arrangement.spacedBy(8.dp)) {
                  Text("Add Image", style = MaterialTheme.typography.titleMedium)                      
                  Spacer(modifier = Modifier.height(8.dp))                                               
                  TextButton(onClick = { showImageSheet = false; val f =                               
  ImageUtils.createImageFile(context); cameraImageFile = f;                                              
  cameraLauncher.launch(ImageUtils.getUriForFile(context, f)) }, modifier = Modifier.fillMaxWidth()) { 
                      Icon(Icons.Default.CameraAlt, contentDescription = null); Spacer(modifier =        
  Modifier.size(8.dp)); Text("Take Photo")                  
                  }                                                                                      
                  TextButton(onClick = { showImageSheet = false; galleryLauncher.launch(androidx.activity
  .result.PickVisualMediaRequest(ActivityResultContracts.PickVisualMedia.ImageOnly)) }, modifier =
  Modifier.fillMaxWidth()) {                                                                             
                      Icon(Icons.Default.PhotoLibrary, contentDescription = null); Spacer(modifier =     
  Modifier.size(8.dp)); Text("Choose from Gallery")
                  }                                                                                      
                  Spacer(modifier = Modifier.height(16.dp)) 
              }
          }                                                                                            
      }                                                                                                  
  }                               
                                                                                                         
  === ui/theme/Color.kt ===                                 
  package com.example.marketplace.ui.theme

  import androidx.compose.ui.graphics.Color                                                            
                                                                                                         
  val Purple80 = Color(0xFFD0BCFF)
  val PurpleGrey80 = Color(0xFFCCC2DC)                                                                   
  val Pink80 = Color(0xFFEFB8C8)                                                                         
  val Purple40 = Color(0xFF6650a4)
  val PurpleGrey40 = Color(0xFF625b71)                                                                   
  val Pink40 = Color(0xFF7D5260)                                                                         
                                                                                                       
  === ui/theme/Type.kt ===                                                                               
  package com.example.marketplace.ui.theme                                                             
                                                                                                         
  import androidx.compose.material3.Typography              
  import androidx.compose.ui.text.TextStyle                                                              
  import androidx.compose.ui.text.font.FontFamily           
  import androidx.compose.ui.text.font.FontWeight
  import androidx.compose.ui.unit.sp                                                                   
                                                                                                         
  val Typography = Typography(    
      bodyLarge = TextStyle(fontFamily = FontFamily.Default, fontWeight = FontWeight.Normal, fontSize =  
  16.sp, lineHeight = 24.sp, letterSpacing = 0.5.sp)        
  )                                                                                                    
                                                                                                         
  === ui/theme/Theme.kt ===       
  package com.example.marketplace.ui.theme                                                               
                                                            
  import android.app.Activity
  import android.os.Build
  import androidx.compose.foundation.isSystemInDarkTheme
  import androidx.compose.material3.*
  import androidx.compose.runtime.Composable                                                           
  import androidx.compose.ui.platform.LocalContext                                                       
                                  
  private val DarkColorScheme = darkColorScheme(primary = Purple80, secondary = PurpleGrey80, tertiary = 
  Pink80)                                                                                              
  private val LightColorScheme = lightColorScheme(primary = Purple40, secondary = PurpleGrey40, tertiary 
                                  
  @Composable                                                                                            
  fun MarketPlaceTheme(darkTheme: Boolean = isSystemInDarkTheme(), dynamicColor: Boolean = true, content:
   @Composable () -> Unit) {                                                                             
      val colorScheme = when {                                                                           
          dynamicColor && Build.VERSION.SDK_INT >= Build.VERSION_CODES.S -> {                          
              val context = LocalContext.current                                                         
              if (darkTheme) dynamicDarkColorScheme(context) else dynamicLightColorScheme(context)
          }                                                                                              
          darkTheme -> DarkColorScheme                                                                 
          else -> LightColorScheme                                                                       
      }                           
      MaterialTheme(colorScheme = colorScheme, typography = Typography, content = content)               
  }                                                                                                      
                                  
  ---                                                                                                    
                                                                                                       
  IMPORTANT NOTES:                                                                                       
  1. Create a new Android project in Android Studio first using "Empty Activity" template, package name
  com.example.marketplace, minimum SDK 24, language Kotlin, Build configuration Kotlin DSL.              
  2. Replace the auto-generated libs.versions.toml, build.gradle.kts files with the ones above.
  3. Create all Kotlin files in src/main/java/com/example/marketplace/ matching the package paths shown.
  4. Create the XML resource files in src/main/res/xml/.                                                 
  5. The project uses a mock API (no real server needed) — 20 seed listings load automatically.        
  6. Do NOT add any extra files or libraries beyond what is listed. Do NOT modify any logic.
# test
