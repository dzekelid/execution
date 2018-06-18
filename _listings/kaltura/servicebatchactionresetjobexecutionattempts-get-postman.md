{
  "info": {
    "name": "Kaltura VPaaS Get Service Batch Action Resetjobexecutionattempts",
    "_postman_id": "c2ae7499-1e97-4555-a344-df3d6562b1e0",
    "description": "batch resetJobExecutionAttempts action resets the execution attempts of the job",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Service",
      "item": [
        {
          "id": "de5c2ac5-0ab5-43d1-a354-ebd0d51c6a7d",
          "name": "batch.addBulkUploadResult",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/batch/action/addBulkUploadResult?bulkUploadResult[accessControlProfileId]=%7B%7D&bulkUploadResult[action]=%7B%7D&bulkUploadResult[appearInList]=%7B%7D&bulkUploadResult[bulkUploadJobId]=%7B%7D&bulkUploadResult[bulkUploadResultObjectType]=%7B%7D&bulkUploadResult[categoryId]=%7B%7D&bulkUploadResult[categoryReferenceId]=%7B%7D&bulkUploadResult[category]=%7B%7D&bulkUploadResult[city]=%7B%7D&bulkUploadResult[contentType]=%7B%7D&bulkUploadResult[contributionPolicy]=%7B%7D&bulkUploadResult[conversionProfileId]=%7B%7D&bulkUploadResult[country]=%7B%7D&bulkUploadResult[creatorId]=%7B%7D&bulkUploadResult[dateOfBirth]=%7B%7D&bulkUploadResult[defaultPermissionLevel]=%7B%7D&bulkUploadResult[description]=%7B%7D&bulkUploadResult[email]=%7B%7D&bulkUploadResult[entitledUsersEdit]=%7B%7D&bulkUploadResult[entitledUsersPublish]=%7B%7D&bulkUploadResult[entryId]=%7B%7D&bulkUploadResult[entryStatus]=%7B%7D&bulkUploadResult[errorCode]=%7B%7D&bulkUploadResult[errorDescription]=%7B%7D&bulkUploadResult[errorType]=%7B%7D&bulkUploadResult[firstName]=%7B%7D&bulkUploadResult[gender]=%7B%7D&bulkUploadResult[group]=%7B%7D&bulkUploadResult[inheritanceType]=%7B%7D&bulkUploadResult[lastName]=%7B%7D&bulkUploadResult[lineIndex]=%7B%7D&bulkUploadResult[moderation]=%7B%7D&bulkUploadResult[name]=%7B%7D&bulkUploadResult[objectErrorDescription]=%7B%7D&bulkUploadResult[objectId]=%7B%7D&bulkUploadResult[objectStatus]=%7B%7D&bulkUploadResult[objectType]=%7B%7D&bulkUploadResult[ownerId]=%7B%7D&bulkUploadResult[owner]=%7B%7D&bulkUploadResult[parentSystemName]=%7B%7D&bulkUploadResult[parentType]=%7B%7D&bulkUploadResult[partnerData]=%7B%7D&bulkUploadResult[partnerId]=%7B%7D&bulkUploadResult[partnerSortValue]=%7B%7D&bulkUploadResult[permissionLevel]=%7B%7D&bulkUploadResult[pluginsData]=%7B%7D&bulkUploadResult[privacy]=%7B%7D&bulkUploadResult[referenceId]=%7B%7D&bulkUploadResult[relativePath]=%7B%7D&bulkUploadResult[requiredObjectStatus]=%7B%7D&bulkUploadResult[resourceId]=%7B%7D&bulkUploadResult[rowData]=%7B%7D&bulkUploadResult[scheduleEndDate]=%7B%7D&bulkUploadResult[scheduleStartDate]=%7B%7D&bulkUploadResult[screenName]=%7B%7D&bulkUploadResult[sshKeyPassphrase]=%7B%7D&bulkUploadResult[sshPrivateKey]=%7B%7D&bulkUploadResult[sshPublicKey]=%7B%7D&bulkUploadResult[state]=%7B%7D&bulkUploadResult[status]=%7B%7D&bulkUploadResult[systemName]=%7B%7D&bulkUploadResult[tags]=%7B%7D&bulkUploadResult[templateEntryId]=%7B%7D&bulkUploadResult[thumbnailSaved]=%7B%7D&bulkUploadResult[thumbnailUrl]=%7B%7D&bulkUploadResult[title]=%7B%7D&bulkUploadResult[type]=%7B%7D&bulkUploadResult[updateMethod]=%7B%7D&bulkUploadResult[url]=%7B%7D&bulkUploadResult[userId]=%7B%7D&bulkUploadResult[userJoinPolicy]=%7B%7D&bulkUploadResult[zip]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "batch addBulkUploadResultAction action adds KalturaBulkUploadResult to the DB"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "10c610a2-9519-445f-9475-25d56698f5a7"
            }
          ]
        },
        {
          "id": "f1e22662-41c7-456e-82e6-7fb9a1bc409f",
          "name": "batch.addMediaInfo",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/batch/action/addMediaInfo?mediaInfo[audioBitRateMode]=%7B%7D&mediaInfo[audioBitRate]=%7B%7D&mediaInfo[audioChannels]=%7B%7D&mediaInfo[audioCodecId]=%7B%7D&mediaInfo[audioDuration]=%7B%7D&mediaInfo[audioFormat]=%7B%7D&mediaInfo[audioResolution]=%7B%7D&mediaInfo[audioSamplingRate]=%7B%7D&mediaInfo[complexityValue]=%7B%7D&mediaInfo[containerBitRate]=%7B%7D&mediaInfo[containerDuration]=%7B%7D&mediaInfo[containerFormat]=%7B%7D&mediaInfo[containerId]=%7B%7D&mediaInfo[containerProfile]=%7B%7D&mediaInfo[contentStreams]=%7B%7D&mediaInfo[fileSize]=%7B%7D&mediaInfo[flavorAssetId]=%7B%7D&mediaInfo[isFastStart]=%7B%7D&mediaInfo[maxGOP]=%7B%7D&mediaInfo[multiStreamInfo]=%7B%7D&mediaInfo[multiStream]=%7B%7D&mediaInfo[rawData]=%7B%7D&mediaInfo[scanType]=%7B%7D&mediaInfo[videoBitRateMode]=%7B%7D&mediaInfo[videoBitRate]=%7B%7D&mediaInfo[videoCodecId]=%7B%7D&mediaInfo[videoDar]=%7B%7D&mediaInfo[videoDuration]=%7B%7D&mediaInfo[videoFormat]=%7B%7D&mediaInfo[videoFrameRate]=%7B%7D&mediaInfo[videoHeight]=%7B%7D&mediaInfo[videoRotation]=%7B%7D&mediaInfo[videoWidth]=%7B%7D&mediaInfo[writingLib]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "batch addMediaInfoAction action saves a media info object"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "669b9267-56df-4b0b-affe-0546e91cfd02"
            }
          ]
        },
        {
          "id": "cf257148-787f-4a4d-ab61-82becd8b543f",
          "name": "batch.checkEntryIsDone",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/batch/action/checkEntryIsDone?batchJobId=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "batch checkEntryIsDone Check weather a specified entry is done converting and changes it to ready."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5d16289a-d71b-442b-be81-76b51be1a203"
            }
          ]
        },
        {
          "id": "18287dea-7d67-4e45-a2e2-b6034cb5283f",
          "name": "batch.checkFileExists",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/batch/action/checkFileExists?localPath=%7B%7D&No Name=%7B%7D&size=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "batch checkFileExists action check if the file exists"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "00e4bb56-6596-46ae-a48b-0d3c1e12bc98"
            }
          ]
        },
        {
          "id": "f4553461-a696-405d-9b29-480923589a22",
          "name": "batch.cleanExclusiveJobs",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/batch/action/cleanExclusiveJobs?No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "batch cleanExclusiveJobs action mark as fatal error all expired jobs"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6cc4fa56-eaac-40f7-a761-40e817722cc2"
            }
          ]
        },
        {
          "id": "ab8e12f5-ddae-43a8-8bad-3fdbfbe2880a",
          "name": "batch.countBulkUploadEntries",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/batch/action/countBulkUploadEntries?bulkUploadJobId=%7B%7D&bulkUploadObjectType=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns total created entries count and total error entries count"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f75a7e28-e85a-4652-a10e-dc1a228cf450"
            }
          ]
        },
        {
          "id": "6fb6f367-9f62-4045-b324-97303bad115c",
          "name": "batch.freeExclusiveJob",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/batch/action/freeExclusiveJob?id=%7B%7D&jobType=%7B%7D&lockKey[batchIndex]=%7B%7D&lockKey[schedulerId]=%7B%7D&lockKey[workerId]=%7B%7D&No Name=%7B%7D&resetExecutionAttempts=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "batch freeExclusiveJobAction action allows to get a generic BatchJob"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "312fe571-969a-4cbf-9358-abe6290f138a"
            }
          ]
        },
        {
          "id": "e0aeca27-0ed7-4787-914c-5dceff62f4c6",
          "name": "batch.getBulkUploadLastResult",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/batch/action/getBulkUploadLastResult?bulkUploadJobId=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "batch getBulkUploadLastResultAction action returns the last result of the bulk upload"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "91d5d811-a228-4cb9-923e-41b4c722d279"
            }
          ]
        },
        {
          "id": "990c1b3c-6807-47a8-b853-c3dfce1a9dc4",
          "name": "batch.getExclusiveAlmostDone",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/batch/action/getExclusiveAlmostDone?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[batchVersionEqual]=%7B%7D&filter[batchVersionGreaterThanOrEqual]=%7B%7D&filter[batchVersionLessThanOrEqual]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=%7B%7D&filter[entryIdEqual]=%7B%7D&filter[errNumberEqual]=%7B%7D&filter[errNumberIn]=%7B%7D&filter[errNumberNotIn]=%7B%7D&filter[errTypeEqual]=%7B%7D&filter[errTypeIn]=%7B%7D&filter[errTypeNotIn]=%7B%7D&filter[estimatedEffortGreaterThan]=%7B%7D&filter[estimatedEffortLessThan]=%7B%7D&filter[executionAttemptsGreaterThanOrEqual]=%7B%7D&filter[executionAttemptsLessThanOrEqual]=%7B%7D&filter[finishTimeGreaterThanOrEqual]=%7B%7D&filter[finishTimeLessThanOrEqual]=%7B%7D&filter[idEqual]=%7B%7D&filter[idGreaterThanOrEqual]=%7B%7D&filter[jobSubTypeEqual]=%7B%7D&filter[jobSubTypeIn]=%7B%7D&filter[jobSubTypeNotIn]=%7B%7D&filter[jobTypeAndSubTypeIn]=%7B%7D&filter[jobTypeEqual]=%7B%7D&filter[jobTypeIn]=%7B%7D&filter[jobTypeNotIn]=%7B%7D&filter[lockVersionGreaterThanOrEqual]=%7B%7D&filter[lockVersionLessThanOrEqual]=%7B%7D&filter[objectType]=%7B%7D&filter[orderBy]=%7B%7D&filter[partnerIdEqual]=%7B%7D&filter[partnerIdIn]=%7B%7D&filter[partnerIdNotIn]=%7B%7D&filter[priorityEqual]=%7B%7D&filter[priorityGreaterThanOrEqual]=%7B%7D&filter[priorityIn]=%7B%7D&filter[priorityLessThanOrEqual]=%7B%7D&filter[priorityNotIn]=%7B%7D&filter[queueTimeGreaterThanOrEqual]=%7B%7D&filter[queueTimeLessThanOrEqual]=%7B%7D&filter[statusEqual]=%7B%7D&filter[statusIn]=%7B%7D&filter[statusNotIn]=%7B%7D&filter[updatedAtGreaterThanOrEqual]=%7B%7D&filter[updatedAtLessThanOrEqual]=%7B%7D&filter[urgencyGreaterThanOrEqual]=%7B%7D&filter[urgencyLessThanOrEqual]=%7B%7D&jobType=%7B%7D&lockKey[batchIndex]=%7B%7D&lockKey[schedulerId]=%7B%7D&lockKey[workerId]=%7B%7D&maxExecutionTime=%7B%7D&No Name=%7B%7D&numberOfJobs=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "batch getExclusiveAlmostDone action allows to get a BatchJob that wait for remote closure"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0e4ab5a3-5ffe-47c9-9310-bdc0686da49e"
            }
          ]
        },
        {
          "id": "f4f8057f-142b-4f7c-bd37-33166a30acd9",
          "name": "batch.getExclusiveJobs",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/batch/action/getExclusiveJobs?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[batchVersionEqual]=%7B%7D&filter[batchVersionGreaterThanOrEqual]=%7B%7D&filter[batchVersionLessThanOrEqual]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=%7B%7D&filter[entryIdEqual]=%7B%7D&filter[errNumberEqual]=%7B%7D&filter[errNumberIn]=%7B%7D&filter[errNumberNotIn]=%7B%7D&filter[errTypeEqual]=%7B%7D&filter[errTypeIn]=%7B%7D&filter[errTypeNotIn]=%7B%7D&filter[estimatedEffortGreaterThan]=%7B%7D&filter[estimatedEffortLessThan]=%7B%7D&filter[executionAttemptsGreaterThanOrEqual]=%7B%7D&filter[executionAttemptsLessThanOrEqual]=%7B%7D&filter[finishTimeGreaterThanOrEqual]=%7B%7D&filter[finishTimeLessThanOrEqual]=%7B%7D&filter[idEqual]=%7B%7D&filter[idGreaterThanOrEqual]=%7B%7D&filter[jobSubTypeEqual]=%7B%7D&filter[jobSubTypeIn]=%7B%7D&filter[jobSubTypeNotIn]=%7B%7D&filter[jobTypeAndSubTypeIn]=%7B%7D&filter[jobTypeEqual]=%7B%7D&filter[jobTypeIn]=%7B%7D&filter[jobTypeNotIn]=%7B%7D&filter[lockVersionGreaterThanOrEqual]=%7B%7D&filter[lockVersionLessThanOrEqual]=%7B%7D&filter[objectType]=%7B%7D&filter[orderBy]=%7B%7D&filter[partnerIdEqual]=%7B%7D&filter[partnerIdIn]=%7B%7D&filter[partnerIdNotIn]=%7B%7D&filter[priorityEqual]=%7B%7D&filter[priorityGreaterThanOrEqual]=%7B%7D&filter[priorityIn]=%7B%7D&filter[priorityLessThanOrEqual]=%7B%7D&filter[priorityNotIn]=%7B%7D&filter[queueTimeGreaterThanOrEqual]=%7B%7D&filter[queueTimeLessThanOrEqual]=%7B%7D&filter[statusEqual]=%7B%7D&filter[statusIn]=%7B%7D&filter[statusNotIn]=%7B%7D&filter[updatedAtGreaterThanOrEqual]=%7B%7D&filter[updatedAtLessThanOrEqual]=%7B%7D&filter[urgencyGreaterThanOrEqual]=%7B%7D&filter[urgencyLessThanOrEqual]=%7B%7D&jobType=%7B%7D&lockKey[batchIndex]=%7B%7D&lockKey[schedulerId]=%7B%7D&lockKey[workerId]=%7B%7D&maxExecutionTime=%7B%7D&maxJobToPullForCache=%7B%7D&No Name=%7B%7D&numberOfJobs=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "batch getExclusiveJobsAction action allows to get a BatchJob"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e87e1e01-076e-4a74-9f13-da4c0379e520"
            }
          ]
        },
        {
          "id": "3688c005-a093-4511-9e85-dc90b7ceed20",
          "name": "batch.getExclusiveNotificationJobs",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/batch/action/getExclusiveNotificationJobs?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[batchVersionEqual]=%7B%7D&filter[batchVersionGreaterThanOrEqual]=%7B%7D&filter[batchVersionLessThanOrEqual]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=%7B%7D&filter[entryIdEqual]=%7B%7D&filter[errNumberEqual]=%7B%7D&filter[errNumberIn]=%7B%7D&filter[errNumberNotIn]=%7B%7D&filter[errTypeEqual]=%7B%7D&filter[errTypeIn]=%7B%7D&filter[errTypeNotIn]=%7B%7D&filter[estimatedEffortGreaterThan]=%7B%7D&filter[estimatedEffortLessThan]=%7B%7D&filter[executionAttemptsGreaterThanOrEqual]=%7B%7D&filter[executionAttemptsLessThanOrEqual]=%7B%7D&filter[finishTimeGreaterThanOrEqual]=%7B%7D&filter[finishTimeLessThanOrEqual]=%7B%7D&filter[idEqual]=%7B%7D&filter[idGreaterThanOrEqual]=%7B%7D&filter[jobSubTypeEqual]=%7B%7D&filter[jobSubTypeIn]=%7B%7D&filter[jobSubTypeNotIn]=%7B%7D&filter[jobTypeAndSubTypeIn]=%7B%7D&filter[jobTypeEqual]=%7B%7D&filter[jobTypeIn]=%7B%7D&filter[jobTypeNotIn]=%7B%7D&filter[lockVersionGreaterThanOrEqual]=%7B%7D&filter[lockVersionLessThanOrEqual]=%7B%7D&filter[objectType]=%7B%7D&filter[orderBy]=%7B%7D&filter[partnerIdEqual]=%7B%7D&filter[partnerIdIn]=%7B%7D&filter[partnerIdNotIn]=%7B%7D&filter[priorityEqual]=%7B%7D&filter[priorityGreaterThanOrEqual]=%7B%7D&filter[priorityIn]=%7B%7D&filter[priorityLessThanOrEqual]=%7B%7D&filter[priorityNotIn]=%7B%7D&filter[queueTimeGreaterThanOrEqual]=%7B%7D&filter[queueTimeLessThanOrEqual]=%7B%7D&filter[statusEqual]=%7B%7D&filter[statusIn]=%7B%7D&filter[statusNotIn]=%7B%7D&filter[updatedAtGreaterThanOrEqual]=%7B%7D&filter[updatedAtLessThanOrEqual]=%7B%7D&filter[urgencyGreaterThanOrEqual]=%7B%7D&filter[urgencyLessThanOrEqual]=%7B%7D&lockKey[batchIndex]=%7B%7D&lockKey[schedulerId]=%7B%7D&lockKey[workerId]=%7B%7D&maxExecutionTime=%7B%7D&No Name=%7B%7D&numberOfJobs=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "batch getExclusiveNotificationJob action allows to get a BatchJob of type NOTIFICATION"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d790c5df-c194-47a5-9625-2fc4d4fcff85"
            }
          ]
        },
        {
          "id": "b9cfd3a0-b5d8-4573-b817-c1849c44d714",
          "name": "batch.getQueueSize",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/batch/action/getQueueSize?No Name=%7B%7D&workerQueueFilter[filter][advancedSearch][attribute]=%7B%7D&workerQueueFilter[filter][advancedSearch][categoriesMatchOr]=%7B%7D&workerQueueFilter[filter][advancedSearch][categoryEntryStatusIn]=%7B%7D&workerQueueFilter[filter][advancedSearch][categoryIdEqual]=%7B%7D&workerQueueFilter[filter][advancedSearch][comparison]=%7B%7D&workerQueueFilter[filter][advancedSearch][contentLike]=%7B%7D&workerQueueFilter[filter][advancedSearch][contentMultiLikeAnd]=%7B%7D&workerQueueFilter[filter][advancedSearch][contentMultiLikeOr]=%7B%7D&workerQueueFilter[filter][advancedSearch][cuePointsFreeText]=%7B%7D&workerQueueFilter[filter][advancedSearch][cuePointSubTypeEqual]=%7B%7D&workerQueueFilter[filter][advancedSearch][cuePointTypeIn]=%7B%7D&workerQueueFilter[filter][advancedSearch][depthGreaterThanEqual]=%7B%7D&workerQueueFilter[filter][advancedSearch][distributionProfileId]=%7B%7D&workerQueueFilter[filter][advancedSearch][distributionSunStatus]=%7B%7D&workerQueueFilter[filter][advancedSearch][entryDistributionFlag]=%7B%7D&workerQueueFilter[filter][advancedSearch][entryDistributionStatus]=%7B%7D&workerQueueFilter[filter][advancedSearch][entryDistributionValidationErrors]=%7B%7D&workerQueueFilter[filter][advancedSearch][extendedStatusEqual]=%7B%7D&workerQueueFilter[filter][advancedSearch][extendedStatusIn]=%7B%7D&workerQueueFilter[filter][advancedSearch][field]=%7B%7D&workerQueueFilter[filter][advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&workerQueueFilter[filter][advancedSearch][idEqual]=%7B%7D&workerQueueFilter[filter][advancedSearch][idIn]=%7B%7D&workerQueueFilter[filter][advancedSearch][indexIdGreaterThan]=%7B%7D&workerQueueFilter[filter][advancedSearch][isQuiz]=%7B%7D&workerQueueFilter[filter][advancedSearch][items]=%7B%7D&workerQueueFilter[filter][advancedSearch][memberIdEq]=%7B%7D&workerQueueFilter[filter][advancedSearch][memberIdIn]=%7B%7D&workerQueueFilter[filter][advancedSearch][memberPermissionsMatchAnd]=%7B%7D&workerQueueFilter[filter][advancedSearch][memberPermissionsMatchOr]=%7B%7D&workerQueueFilter[filter][advancedSearch][metadataProfileId]=%7B%7D&workerQueueFilter[filter][advancedSearch][noDistributionProfiles]=%7B%7D&workerQueueFilter[filter][advancedSearch][not]=%7B%7D&workerQueueFilter[filter][advancedSearch][objectType]=%7B%7D&workerQueueFilter[filter][advancedSearch][orderBy]=%7B%7D&workerQueueFilter[filter][advancedSearch][type]=%7B%7D&workerQueueFilter[filter][advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&workerQueueFilter[filter][advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&workerQueueFilter[filter][advancedSearch][userIdEqual]=%7B%7D&workerQueueFilter[filter][advancedSearch][userIdIn]=%7B%7D&workerQueueFilter[filter][advancedSearch][value]=%7B%7D&workerQueueFilter[filter][advancedSearch][watermarkId]=%7B%7D&workerQueueFilter[filter][batchVersionEqual]=%7B%7D&workerQueueFilter[filter][batchVersionGreaterThanOrEqual]=%7B%7D&workerQueueFilter[filter][batchVersionLessThanOrEqual]=%7B%7D&workerQueueFilter[filter][createdAtGreaterThanOrEqual]=%7B%7D&workerQueueFilter[filter][createdAtLessThanOrEqual]=%7B%7D&workerQueueFilter[filter][entryIdEqual]=%7B%7D&workerQueueFilter[filter][errNumberEqual]=%7B%7D&workerQueueFilter[filter][errNumberIn]=%7B%7D&workerQueueFilter[filter][errNumberNotIn]=%7B%7D&workerQueueFilter[filter][errTypeEqual]=%7B%7D&workerQueueFilter[filter][errTypeIn]=%7B%7D&workerQueueFilter[filter][errTypeNotIn]=%7B%7D&workerQueueFilter[filter][estimatedEffortGreaterThan]=%7B%7D&workerQueueFilter[filter][estimatedEffortLessThan]=%7B%7D&workerQueueFilter[filter][executionAttemptsGreaterThanOrEqual]=%7B%7D&workerQueueFilter[filter][executionAttemptsLessThanOrEqual]=%7B%7D&workerQueueFilter[filter][finishTimeGreaterThanOrEqual]=%7B%7D&workerQueueFilter[filter][finishTimeLessThanOrEqual]=%7B%7D&workerQueueFilter[filter][idEqual]=%7B%7D&workerQueueFilter[filter][idGreaterThanOrEqual]=%7B%7D&workerQueueFilter[filter][jobSubTypeEqual]=%7B%7D&workerQueueFilter[filter][jobSubTypeIn]=%7B%7D&workerQueueFilter[filter][jobSubTypeNotIn]=%7B%7D&workerQueueFilter[filter][jobTypeAndSubTypeIn]=%7B%7D&workerQueueFilter[filter][jobTypeEqual]=%7B%7D&workerQueueFilter[filter][jobTypeIn]=%7B%7D&workerQueueFilter[filter][jobTypeNotIn]=%7B%7D&workerQueueFilter[filter][lockVersionGreaterThanOrEqual]=%7B%7D&workerQueueFilter[filter][lockVersionLessThanOrEqual]=%7B%7D&workerQueueFilter[filter][objectType]=%7B%7D&workerQueueFilter[filter][orderBy]=%7B%7D&workerQueueFilter[filter][partnerIdEqual]=%7B%7D&workerQueueFilter[filter][partnerIdIn]=%7B%7D&workerQueueFilter[filter][partnerIdNotIn]=%7B%7D&workerQueueFilter[filter][priorityEqual]=%7B%7D&workerQueueFilter[filter][priorityGreaterThanOrEqual]=%7B%7D&workerQueueFilter[filter][priorityIn]=%7B%7D&workerQueueFilter[filter][priorityLessThanOrEqual]=%7B%7D&workerQueueFilter[filter][priorityNotIn]=%7B%7D&workerQueueFilter[filter][queueTimeGreaterThanOrEqual]=%7B%7D&workerQueueFilter[filter][queueTimeLessThanOrEqual]=%7B%7D&workerQueueFilter[filter][statusEqual]=%7B%7D&workerQueueFilter[filter][statusIn]=%7B%7D&workerQueueFilter[filter][statusNotIn]=%7B%7D&workerQueueFilter[filter][updatedAtGreaterThanOrEqual]=%7B%7D&workerQueueFilter[filter][updatedAtLessThanOrEqual]=%7B%7D&workerQueueFilter[filter][urgencyGreaterThanOrEqual]=%7B%7D&workerQueueFilter[filter][urgencyLessThanOrEqual]=%7B%7D&workerQueueFilter[jobType]=%7B%7D&workerQueueFilter[schedulerId]=%7B%7D&workerQueueFilter[workerId]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "batch getQueueSize action get the queue size for job type"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a8d55348-cd0a-4a9f-8f38-b04c3d23058b"
            }
          ]
        },
        {
          "id": "b93c92fd-f11c-4a56-8cf2-df064842ef1c",
          "name": "batch.logConversion",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/batch/action/logConversion?data=%7B%7D&flavorAssetId=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Add the data to the flavor asset conversion log, creates it if doesn't exists"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7f8f451a-cc4c-4c26-9396-a1ad2f7e8bd2"
            }
          ]
        },
        {
          "id": "d19869cd-0eaa-4a41-9758-9a25e13b9735",
          "name": "batch.resetJobExecutionAttempts",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/batch/action/resetJobExecutionAttempts?id=%7B%7D&jobType=%7B%7D&lockKey[batchIndex]=%7B%7D&lockKey[schedulerId]=%7B%7D&lockKey[workerId]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "batch resetJobExecutionAttempts action resets the execution attempts of the job"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d7ff8724-f7b0-4726-b5fc-ec08db5e2a63"
            }
          ]
        }
      ]
    }
  ]
}