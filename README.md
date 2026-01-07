# cicd-actions

 docker run -d -p ${{ inputs.app_port }}:${{ inputs.app_port }} \
             -e ENV=${{ inputs.environment }} \
             --name ${{ inputs.app_name }} ${{ inputs.app_name }}
