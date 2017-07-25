# ChangeLog

### AdZodiac v0.3.001-beta `2017-07-25`

1. Update version encoding rules
2. Fix an error of missing AdUUID in cloning of percentage
3. Fix an error of mIsInit in reloading ad
4. We change to use ad id to identify the index in list
5. We add the condition of size = 0 in FrescoNativeImageHelper
6. Fix the bug in disabled main and icon images
7. Remove evictFromMemoryCache in destroy

### AdZodiac v0.2.45-beta `2017-07-21`

1. Check context in custom networks
2. Remove evictFromMemoryCache in clear method
3. Update fresco library from 0.12.0 to 1.4.0

### AdZodiac v0.2.42-beta `2017-07-17`

1. Add a choice of fill event in recorder

### AdZodiac v0.2.41-beta `2017-07-14`

1. Refine loading position and percentage schema
2. Check third-party libraries

### AdZodiac v0.2.39-beta `2017-07-07`

1. Add the check of NoClassDefFoundError in external networks

### AdZodiac v0.2.37-beta `2017-07-05`

1. Release the control of ScaleType
2. Adjust the check of AdMob ad assets

### AdZodiac v0.2.36-beta `2017-07-03`

1. Add a backup buffer for NativeAd
2. Fix the process of new ImpressionTracker

### AdZodiac v0.2.35-beta `2017-06-29`

1. Re-write to the cache for each update in percentages

### AdZodiac v0.2.34-beta `2017-06-27`

1. Add AdZodiacAdOptions
2. Fix a retry scheme bug in AdView

### AdZodiac v0.2.32-beta `2017-06-20`

1. Add video enabled ads in AdMob renderer

### AdZodiac v0.2.31-beta `2017-06-13`

1. Update the list of KeywordParameters

### AdZodiac v0.2.28-beta `2017-06-12`

1. Fix a FrameLayout wraping content bug in AdMob renderer

### AdZodiac v0.2.27-beta `2017-06-09`

1. Fix swapMargins in AdMob renderer
2. Fix a invisible icon problem in AdMob renderer

### AdZodiac v0.2.25-beta `2017-06-06`

1. Fix timeout retry 

### AdZodiac v0.2.22-beta `2017-06-05`

1. Fix wrap content in Fresco

### AdZodiac v0.2.21-beta `2017-06-01`

1. Support list view
2. Support custom stream
3. Fix isoCountryCode

### AdZodiac v0.2.20-beta `2017-05-25`

1. Fix memory leak in clear issues
2. Fix setLayoutParams in MediaView

### AdZodiac v0.2.19-beta `2017-05-23`

1. Fix CustomEventNativeListener in AdZodiacBatchNative
2. Support gif format in image
3. Update FacebookAdRenderer
4. Add timeout check in external networks

### AdZodiac v0.2.17-beta `2017-05-22`

1. Update Fresco evictFromMemoryCache and clearMemoryCaches

### AdZodiac v0.2.16-beta `2017-05-18`

1. Change setActualImageScaleType schema

### AdZodiac v0.2.13-beta `2017-05-15`

1. Fix memory leak in single native.
2. Fix wrap_content in Fresco

### AdZodiac v0.2.10-beta `2017-05-12`

1. Fix memory leak in recyclerview and batch native. 
2. Replace image downloader with Fresco.

### AdZodiac v0.2.7-beta `2017-05-09`

1. Fix AdZodiacSignleNative bug
2. Fix FlurryAgentWrapper bug

### AdZodiac v0.2.6-beta `2017-05-05`

1. Fix retry bug

### AdZodiac v0.2.4-beta `2017-05-05`

1. Change weights when it is failed to load (Native) Ad
2. Parallel replenish cache when it is created.

### AdZodiac v0.2.2-beta `2017-05-02`

1. Change error interface
2. Change log

### AdZodiac v0.2.1-beta `2017-04-27`

1. Add error handler

### AdZodiac v0.1.12-beta `2017-04-27`

1. Change location precision to 4 and TRUNCATED
2. Add AdZodiacImpressionTracker
3. modify AdZodiacBrowser finish()
4. modify GpsHelper internalFetchAdvertisingInfoAsync
5. Add bundle in each request
6. Add external network renderers in sample code

### AdZodiac v0.1.11-beta `2017-04-21`

1. Fix AdZodiacSingleNative bugs
2. Change NativeAdListener method names

### AdZodiac v0.1.10-beta `2017-04-20`

1. Fix AdZodiacBatchNative bugs

### AdZodiac v0.1.9-beta `2017-04-19`

1. Fix external networks
2. Fix event recorder

### AdZodiac v0.1.8-beta `2017-04-18`

1. remove test mode logs

### AdZodiac v0.1.7-beta `2017-04-17`

1. remove AdZodiacRecommend and add AdZodiacBatchNative
2. change db action names

### AdZodiac v0.1.5-beta `2017-04-17`

1. change refreshTime scheme
2. change RecommendationListener
3. add version code in request

### AdZodiac v0.1.3-beta `2017-04-14`

1. Fix setting of CustomerNo, ChannelNo, and BrandNo

### AdZodiac v0.1.2-beta `2017-04-14`

1. Fix typo
2. Change AdZodiacBroswer background setting

### AdZodiac v0.1.0-beta `2017-04-10`

1. Modify proguard rules
2. Fix bugs

### AdZodaic v0.0.4-beta `2017-03-31`

1. add Google external network
2. add AdZodiacSingleNative

### AdZodiac v0.0.1-beta `2017-03-27`

1. Four modes: banner, interstitial, static native, recommendation
2. add keyword parameters
3. change channel, customer, brand number setting policy

