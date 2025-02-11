# template-pipeline

          sam deploy \
            --no-confirm-changeset \
            --stack-name OpenIdConfigurationFunctionSam \
            --capabilities CAPABILITY_IAM || echo "No changes to deploy"
