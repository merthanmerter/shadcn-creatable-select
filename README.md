# shadcn-creatable-select

Creatable select component for shadcn/ui

# usage example

```
<CreatableSelect
    name="industry"
    defaultValue={{
    label: data?.data?.industry || '',
    value: data?.data?.industry || '',
    }}
    isLoading={industriesFetching}
    mutate={industryMutate}
    options={
        industries?.data?.data?.map((industry) => ({
            label: industry.industry,
            value: industry.industry,
        })) || []
     }
/>
```
