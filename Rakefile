repository_dispatch/WORKSFLOW/GETEVENTLISTNER/TOGGLE-ON:AUTOMATES::ALL: EVENTS:rRun::/Runs:
:Build:: Nane
Name: Repository Dispatch
        uses: peter-evans/repository-dispatch@v1
        with:
          token: ${{ secrets.REPO_ACCESS_TOKEN }}
          repository: username/my-repo
          event-type: my-event
          client-payload: '{"ref": "${{ github.ref }}"}"''
